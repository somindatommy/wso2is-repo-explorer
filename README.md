# WSO2 Identity Server Git Repo Explorer (rEx)

## Initial Setup

* **Step:1** Copy rex.sh (from *wso2is-repo-explorer* directory) to a directory where you want to maintain Identity Server git repositories. Alway better to keep this readonly. Also make the script an executable.
```javascript
\> wget https://github.com/prabath/wso2is-repo-explorer/raw/master/rex.sh
\> chmod +x rex.sh
```
* **Step:2** Initialize git repository explorer. This will checkout all Identity Server repositories and will take some time.

```javascript
\> ./rex.sh init
```

## Usage 

* **Clone** all Identity Server related repositories. If you already performed init, you do not need to do this.

```javascript
\> ./rex.sh clone
```

* **List** out all Identity Server related repositories. If you already performed init, you do not need to do this.

```javascript
\> ./rex.sh list
```

* **Find** the git repo, by the name of a Jar file (without the version number)

```javascript
\> ./rex.sh find org.wso2.carbon.identity.authenticator.mutualssl
```
