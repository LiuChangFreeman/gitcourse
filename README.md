<p align="center"><img src="https://kfcoding-static.oss-cn-hangzhou.aliyuncs.com/kfcoding-book-cover/gitcourseguid.png"/></p>

<h1 align="center">Gitcourse</h1>

A react front framework which can present courses made by repositories.  

Here is a sample as well as a guide to this project: [gitcourse-guide](http://gitcourse.kfcoding.com/#https://code.kfcoding.com/liuchangfreeman/gitcourse-guide.git)

## Getting start
### Install 
```bash
npm install gitcourse-core
```
### Usage
```javascript
import ReactDOM from 'react-dom';
import GitCourse from 'gitcourse-core';

ReactDOM.render(
  <GitCourse
    compact={false}
    repo={'${YOUR_GIT_REPOSITORY}'}
    dockerEndpoint={'${YOUR_DOCKER_ENDPOINT_SERVER_HOST}'}
    corsProxy={'${YOUR_GIT_CORS_PROXY}'}
  />
,
  document.getElementById('root')
);
```

If you have a general question about Gitcourse or some suggestions about Gitcourse we encourage you to post on our [slack workspace](https://app.slack.com/client/TPD8HAVMW/CPFELS1AA) . The maintainers and other community members are glad to talk with you.
