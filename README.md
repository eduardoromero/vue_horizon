# vue_horizon

Just a demo of VueJS + Horizon.js

A file sharing web on JavaScript. All shares are persisted thru RethinkDB via Horizon. Which allows us to add more 
functionality later on.

As it is is just one file [upload.html](../blob/master/dist/upload.html). I will refactor it to create a component and 
split the code on several files.

## TODO
Add backend code so you can share the files via E-Mail and a Template so you can share a link to a particular file just like WeTransfer.

## Other things
File uploads are integrated with Uploadcare and saved to a S3 bucket.
