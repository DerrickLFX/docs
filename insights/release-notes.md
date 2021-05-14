# Release Notes

## May 2021

The LFX Insights, May 2021 Release delivers support for new data sources and metrics— GitHub Reviews, Changeset Reviews metrics as source control systems, Circle CI as build system, and Google Groups as Email system to visualize project related communication activities.

* [Added Features](release-notes.md#added-features)
* [Deprecated Features](release-notes.md#deprecated-features)

## Added Features

## Deprecated Features

Following visualizations are deprecated in this release, and the dashboards are updated and enhanced with new visualizations in various data sources:

### GitHub Overview

**Pull Requests by Status Over Time** showed a stacked bar graph that represents the number of open and closed pull requests over time. Mouse over a color in the graph to see the total number of pull requests by status that occurred on a date.

**Pull Request by Organizations Over Time** showed a stacked bar graph that represents the number of pull requests per day by organization over time. Mouse over a color in the graph to see the total number of pull requests that occurred on a date for the organization.

**Pull Requests By Project** showed a table and lists and lets you sort values by project name, number of pull requests, submitters, and repositories per project.

### GitHub Efficiency

**Efficiency Closing GitHub Pull Requests** let you select an organization and project as values for the dashboard data. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**REI** \(Review Efficiency Index\) showed a multi-line graph that represents the REI. REI is defined as the number of closed pull requests divided by the number of open pull requests in a given period of time. This visualization measures efficiency in closing pull requests. REI as a moving average is set to 8 weeks to identify changes in trends. Average is also shown as a reference. REI values greater than 1 mean the community is closing more pull requests than those they are opening. Values smaller than 1 mean the opposite—more pull requests open than those closed during a given time frame. Mouse over this graph or **Lead Time** to show a line that displays the date and time at the top of the legend.

**Time to Merge** shows the time from pull request creation to the moment in which the pull request is closed. The gauge is set to show green color for less than 7 days, yellow for values from 7 to 30 days and red from 30 to 90 days. This setting means that a week is considered as a good time to merge.

**Lead Time** shows a multi-line graph that represents the average time expressed in days between the initiation and completion of a production process, in this case, a pull request. Mouse over this graph or REI to show a line that displays the date and time at the top of the legend.

**Repositories** shows a table with 50th percentile of Median Time Open \(days\) by repository, giving an insight to the differences between them. You can click repository name to open the repository in GitHub.

**Efficiency Closing GitHub Pull Requests:**

**REI**: Review Efficiency Index, defined as the number of closed pull requests divided by the number of open ones in a given period of time. Measures efficiency closing pull requests.

**Lead time**: the time expressed in days between the initiation and completion of a production process, in this case, a pull request. Shown in average.




