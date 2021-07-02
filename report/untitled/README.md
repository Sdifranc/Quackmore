# Report and Features

## Introduction

A report presents the portion of one or more cubes and takes the form of a table and/or graph with different aggregation levels, which can be browsed in depth \(drill down\) according to the natural hierarchy principle.

Reports are created and published by the DAC administrator. You can consult a report directly from the [**catalog** ](../report-catalog.md)or in a page.

A report typically looks like the one in the figure below:

![](../../.gitbook/assets/image%20%2814%29.png)

The report name and its folder are displayed in the top left. Selecting each folder displays its contents and directs browsing back to the catalog.

You can execute the **OLAP functions** directly in the report.

The published reports may be edited, although the edits remain at user session level, in such a way as to give full freedom of analysis, leaving the environment prepared by the DAC administrator unchanged.

The functions available on DAC can be applied using the commands from the:

* \*\*\*\*[**report toolbar**](../repor-toolbar/) _\*\*_
* \*\*\*\*[**pop-up menu**](pop-up-menu.md) to the report cells

Any reports modified using the functions available on DAC will be visible only to the user who made the modification, and they will be kept only until the next login, or when a restart is carried out by the administrator.

After modifying the report, you can use the Reload Report item on the report toolbar \(Main section\) to restore the report to its original form.

Reports can be presented in the form of a table, graph or both \(document\). The user may apply **custom styles** with the:

* **graph**
* **table**

Commands and buttons quickly let you change the **paging** of the report or sort the metrics.

The data can be filtered through the levels placed in the **Report Pages**.

When you open a report, even if recently consulted by you, or if consulted by another user, it is executed again, but it is simply removed from the **cache** of the system.

When publishing a report, specific functionality may only appear on the web:

* the **decoration of the metrics**
* a **prompt** for selecting or analyzing above the report
* a **drill-through** link to open a new page from the analyzed data

