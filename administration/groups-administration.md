# Groups Administration

{% embed url="https://bitbucket.org/decisyon/manual/downloads/Create\_New\_Group.mp4" caption="" %}

## **Overview**

In this unit, you will learn how create a Group and how can be managed.

## Groups Administration

The Group Administration is a function enabled only for the User Administrator.

The group management window is activated from **Main Toolbar &gt;&gt; Administration &gt;&gt; Groups Administration.**

The default "**Everyone**" group created by the system includes all users on the system and includes the permissions to access the application and display all objects of the application. Since the “Everyone” group is generated automatically by the system, you cannot rename it, move it or delete it from its Root.

DAC allows you to make the data reading schema dynamic for the user group. This schema is set during the creation of Cubes and Dimensions, on which the reports are then run.

On the user group, it is possible to customize the permissions on the objects, to enable the view of cubes, dimensions and metrics.

DAC enables or disables the execution of the web events.

A user, to be able to access the logical objects, dimensions, cubes, metrics, must be associated with at least one group.

The users may belong to several groups and inherit all the permissions and assignments of the pertinent groups. In case the permissions defined in the pertinent group clash, the user inherits the most restrictive one: if in a group a granted reading permission on an object is defined \(e.g. a M1 metric\) and in the other group, for the same object, it is instead denied, the user which belongs to the two groups will not have reading access \(i.e. does not see metric M1\).

Permissions are exclusively managed for the DAC Web interface. In particular, when reading an object or a group of objects is denied, they will not be visible in DAC. Moreover, any report using them will not be viewed and an error message will be shown in its place.

