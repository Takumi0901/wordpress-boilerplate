```aidl
docker-compose up -d  
```

```aidl
docker-compose build 
```

```aidl
docker-compose down
```

```aidl
docker volume ls 
```

```aidl
docker volume rm $(docker volume ls -qf dangling=true)
```

```aidl
docker volume ls -qf dangling=true | xargs -r docker volume rm  
```
