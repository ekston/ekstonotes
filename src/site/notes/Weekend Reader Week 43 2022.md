---
{"dg-publish":true,"permalink":"/weekend-reader-week-43-2022/","dgShowBacklinks":true,"dgShowLocalGraph":true,"dgShowInlineTitle":true}
---

---

**Cross-Tenant OneDrive Migration**
Microsoft is looking after companies that have the need to migrate OneDrive content from one tenant to another. Perfect, as cloud adoption has definitely created some need for that functionality - https://learn.microsoft.com/en-gb/microsoft-365/enterprise/cross-tenant-onedrive-migration?view=o365-worldwide

**Cybersecurity is for everyone—this October and all year**
Little summary of what Microsoft offers for this years *Cybersecurity Awareness Month*. This mainly links to Microsoft learning paths, of which I am a big fan - https://techcommunity.microsoft.com/t5/microsoft-learn-blog/cybersecurity-is-for-everyone-this-october-and-all-year/ba-p/2319502#

**What’s new in Security and Management in SharePoint, OneDrive, and Teams – Microsoft Ignite 2022**
Post Ignite is a great time to go through different posts collecting news specific per product. Here we have a summary of Security and Management related announcements for Teams, SharePoint online and OneDrive - https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/what-s-new-in-security-and-management-in-sharepoint-onedrive-and/ba-p/3648912











```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title       Adding GANTT diagram functionality to mermaid
    excludes    weekends
    %% (`excludes` accepts specific dates in YYYY-MM-DD format, days of the week ("sunday") or "weekends", but not the word "weekdays".)

    section A section
    Completed task            :done,    des1, 2014-01-06,2014-01-08
    Active task               :done,  des2, 2014-01-09, 3d
    Future task               :         des3, after des2, 5d
    Future task2              :         des4, after des3, 5d

    section Critical tasks
    Completed task in the critical line :crit, done, 2014-01-06,24h
    Implement parser and jison          :crit, done, after des1, 2d
    Create tests for parser             :crit, active, 3d
    Future task in critical line        :crit, 5d
    Create tests for renderer           :2d
    Add to mermaid                      :1d
    Functionality added                 :milestone, 2014-01-25, 0d

    section Documentation
    Describe gantt syntax               :active, a1, after des1, 3d
    Add gantt diagram to demo page      :after a1  , 20h
    Add another diagram to demo page    :doc1, after a1  , 48h

    section Last section
    Describe gantt syntax               :after doc1, 3d
    Add gantt diagram to demo page      :20h
    Add another diagram to demo page    :48h
```


