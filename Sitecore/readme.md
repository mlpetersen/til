# Sitecore

## Parameters

### Go directly to an ID

Go directly to an ID in Sitecore by appending the `fo={id}` parameter while in the content editor:
```
https://domain.com/sitecore/shell/Applications/Content%20Editor.aspx?fo={ABCDE-FGHI-JKLM-NOPQ-RSTUVW}
```

### View content from the master database

View content from `master` instead of `web`, by appending the `sc_database=master` parameter. Useful for when testing/developing, no need to publish.
```
https://domain.com?sc_database=master 
```

