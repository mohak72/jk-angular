# jk-angular

start angular build
 (ng serve --host 0.0.0.0 --port 4200 &)
https://www.coditty.com/code/how-to-stop-running-agular-started-by-ng-serve
 ps -ef | grep "ng serve"
01   985   981   0 Sun11AM ttys001  2638:30.05 ng serve --port 4222 --ssl     
 501 32539 32446   0 11:53AM ttys009    0:00.00 grep ng serve
kill -9 985
