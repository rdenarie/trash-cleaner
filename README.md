# trash-cleaner

Trash Cleaner Job.

Deploy the addon with ./addon install exo-trash-cleaner

Set configuration options in exo.properties :

trashcleaner.cron.expression=0 0 21 * * ?
trashcleaner.lifetime=0

Cron expression to define when the job is fired
lifetime is the number of days a document stays in trash before being removed by TrashCleanerJob

