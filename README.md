# Mini-Kanban-Logs

Logs containers for Mini-Kanban Project (Mini-Kanban ms, Comments-Kanban ms) using influx db and telegraf

<h2>About the project:</h2>
<p>The main objective of the repo is to create a centralized time series log storage for the events that occur in the Mini-Kanban project. </p>

<h2>Initializing the project</h2>
<p>Start docker and run the following command in your terminal</p>

```
"docker-compose up -d"
```

<p>To acess the application</p>

```
"http://localhost:8086/"
```

```
"http://localhost:15672/"
```

<p>Publish message in the telegraf queue</p>

```
{
"code": 200,
"body": "str body",
"service": "Comments-Kanban",
"method": "GET",
"url": "/comments"
}
```

[Link to access the mini-kanban repository](https://github.com/KevinDaSilvaS/Mini-Kanban "mini-kanban repository")
###
[Link to access the comments-kanban repository](https://github.com/KevinDaSilvaS/comments-kanban "comments-kanban repository")
###
[Link to access the kanban-api-gateway repository](https://github.com/KevinDaSilvaS/kanban-gateway "kanban-gateway repository")
###
[Link to access the old kanban-api-gateway repository](https://github.com/KevinDaSilvaS/kanban-api-gateway "kanban-api-gateway repository")
