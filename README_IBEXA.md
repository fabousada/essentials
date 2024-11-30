
## Ibexa Commands


### Clean Draft version Ibexa
```bash
 php bin/console ibexa:content:cleanup-versions --keep=0
```

Clear Image variation cache
```bash
 php bin/console liip:imagine:cache:remove -v
```

Reindex search

```bash
  php bin/console  ibexa:reindex --no-purge --processes=1
```

Copy from Ibexa to local
```bash
   scp "$(ibexa_cloud ssh--app-app --pipe):/path_to_file /local_folder1/
```

Copy from local to Ibexa to local
```bash
 scp ./foler_local/* "$(ibexa_cloud ssh --app-app-pipe)*: ibexa_folder/
```




