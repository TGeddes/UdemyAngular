Pipes
A single line is knows as a pipe and it looks like: |
All default pipes are on angular.io
You can chain pipes and are applied in the order they are in.
To create pipes the notation for the file is pipeName.pipe.ts
When you have parameters it shows like {{ server.name | shorten:12 }} and if you had a second parameter it would be {{ server.name | shorten:12:anotherParameter }}
If pure is false it will run the pipe anytime the any data is changed on the page.
To output a string that you know will happen but doesn’t happen at the very beginning use async in a pipe.

