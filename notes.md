
<!-- ============= HOW TO CUSTOMISED BOOTSTRAP CLASS FROM SASS =========== -->

video url:https://www.youtube.com/watch?v=DjkwjL0DuZY&ab_channel=AliHossain





========== USING NPM(Node.js) =================

******* Type below command in terminal ********

1) npm init -y ---> (its create package.json )

2) npm install bootstrap  ---> (copy this line from bt-site --> https://getbootstrap.com/docs/5.0/getting-started/download/ )
                          ---> bootsrap downloaded and also its created Node Modules folder

3) <link rel="stylesheet" href="sass/main.css"> --> link main.css in index.html (inside header) file
4)   <script src="node_modules/bootstrap/dist/js/bootstrap.js"></script> --> link bootstap js in index.html (before end body) 

5) @import "../node_modules/bootstrap/scss/bootstrap.scss"; (import bootsrap.scss in main.scss)


Now, we can change bootsrap pre-define class inside the main.scss file
for ex.  // ============== CUSTOMISE BOOTSTRAP CLASS ==============

$primary:red;
$light:green;





NOTE:== 
--> you have to download extension  "live sass compiler" in vs code for compile scss to css..
