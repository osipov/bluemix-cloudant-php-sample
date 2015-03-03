#Cloudant

##Cloudant Document-Oriented (NoSQL) Database

Cloudant is a JSON data store, a type of a NoSQL database that is an excellent fit for multi-structured data, unstructured data and fast-changing data models.

**If you are going to use PHP**

To try the sample Cloudant application, change directory to ```bluemix-cloudant-php-sample``` and then deploy to Bluemix by executing the following commands:

```
cf login
cf create-service cloudantNoSQLDB Shared myCloudant
cf push
```

After the commands complete successfully, look for the console output specifying the application URL. It should look something like 

```
usage: 128M x 1 instances
urls: cloudant-random-word.mybluemix.net
```

Open your favorite browser using the URL ending with mybluemix.net (such as cloudant-random-word.mybluemix.net in the example above) from the console output to access the application. 

**To install PHP pre-requisites for a local deployment** 

Via [Composer](https://getcomposer.org/)

``` bash
$ composer install
```
