---
stack: GO
lang: all
---

## Install go modules
```
go mod init www.github.com/my-repo or my-local
```

## get go-mysql-driver
```
go get -u github.com/go-sql-driver/mysql
```

## Got a problem with lunch? GOPATH should be set to
```
export GOPATH=$GOROOT
unset GOROOT
```

##  GO111MODULE set "on" or "off"
```
go env -w GO111MODULE=off
```

---