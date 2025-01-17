
<div align="center">
<img src="https://socialify.git.ci/ashavijit/MovieX/image?font=Source%20Code%20Pro&forks=1&issues=1&language=1&name=1&owner=1&pattern=Circuit%20Board&pulls=1&stargazers=1&theme=Dark" alt="MovieX" width="640" height="320" />
</div>
<p align="center">
  <h1 align="center">MovieX</h1>
</p>

## Description
MovieX is a web based application that allows user to book tickets for newly released movies in theater. User can search for any movie using the search bar provided and according to their preference they can book tickets for the Movie.

## Technologies Used
* **Front-End :** *ReactJs*
* **Back-End :** *Python3*
* **Backend database :** *MongoDB*
* **API :** *Fast API*
* **Load-balancing :** *Envoy proxy* 
* **Microservices communication :** *gRPC* 
* **Microservices container :** *Docker* 

![](https://img.shields.io/badge/ReactJs-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![](https://img.shields.io/badge/Python3-38B2AC?style=for-the-badge&logo=python)
![](https://img.shields.io/badge/MongoDB-fa1505?style=for-the-badge&logo=mongodb&logoColor=#fa1505)
![](https://img.shields.io/badge/Fast%20API-faea05?style=for-the-badge&logo=fastapi&logoColor=red)
![](https://img.shields.io/badge/Envoy%20Proxy-de92e8?style=for-the-badge)
![](https://img.shields.io/badge/Docker-097049?style=for-the-badge&logo=docker)
![](https://img.shields.io/badge/gRPC-9bed93?style=for-the-badge)

## Features

* you can create your Account from SignUp Page and Access the data from any device anywhere anytime.
* you can Search any Movie From the Search-bar of the application
* you can reserve tickets for movies which are currently streaming in Cinemas.
* you can check your reservation History that shows Every Details of the Reservation

## Screenshots
**1.** Home-Page of Application.

   ![](./screenshots/homepage.png)

**2.** Sign-Up Page.
   
   ![](./screenshots/signup.png)

**3.** Sign-In / Login Page.
   
   ![](./screenshots/login.png)

**4.** Reserve currently playing movies.
   
   ![](./screenshots/reserve.png)

**5.** Reservation history.
   
   ![](./screenshots/Dashboard.png)

**6.** Search by the movie title.
   
   ![](./screenshots/Search.png)

## Installation Guide

Below are the steps to follow to contribute to this project:

**1.** Fork [this](https://github.com/ashavijit/MovieX) repository.

**2.** Clone your forked copy of the project.

```
git clone https://github.com/<your_user_name>/MovieX.git
```

where `your_user_name` is your GitHub username.

**3.** Navigate to the project directory.

```
cd MovieX
```

**4.** Add a reference(remote) to the original repository.

```
git remote add upstream https://github.com/ashavijit/MovieX.git
```

**5.** Check the remotes for this repository.

```
git remote -v
```

**6.** Always take a pull from the upstream repository to your main branch to keep it at par with the main project(updated repository). Feel free to raise new issues.

```
git pull upstream main
```

**7.** Create a new branch.

```
git checkout -b <your_branch_name>
```

**8.** Make Sure Docker is installed in your Device if not please install Docker

**9.** Docker Compose build

```
$ docker-compose build
```

**10.** Docker Compose Up
```
$ docker-compose up
```
you are ready to make changes to the project

**11.** Please Change the PORT Number in the ```docker-compose.yml``` file.

**12.** After installation, go to the URL: `http://localhost:3000/`.

**13.** Make necessary changes and commit those changes

**14.** Track your changes.

```
git add .
```

**15.** Commit your changes .

```
git commit -m "bla bla bla"
```

**16.** Push the committed changes in your feature branch to your remote repo.

```
git push -u origin <your_branch_name>
```

**17.** To create a pull request, click on `Compare & pull request`. Please ensure you compare your feature branch to the desired branch of the repo you are suppose to make a PR to.

**18.** Add appropriate title and description to your pull request explaining your changes and efforts done.

**19.** Click on `Create pull request`.

**20.** Congrats!! you are done creating a pull request to this project. 

**21.**  After this, the maintainers will review the PR and will merge it if it helps move the project forward. Otherwise, it will be given constructive feedback and suggestions for the changes needed to add the PR to the codebase.

## Folder Structure
<pre>
.
└── <a href="https://github.com/ashavijit/MovieX">MovieX/</a>
    ├── <a href="https://github.com/ashavijit/MovieX/tree/main/envoy">Envoy/</a>
    ├── <a href="https://github.com/ashavijit/MovieX/tree/main/frontend">Frontend/</a>
    │   ├── <a href="https://github.com/ashavijit/MovieX/tree/main/frontend/public">public/</a>
    │   │   └── <a href="https://github.com/ashavijit/MovieX/tree/main/frontend/public/images">images</a>
    │   └── <a href="https://github.com/ashavijit/MovieX/tree/main/frontend/src">src/</a>
    │       ├── <a href="https://github.com/ashavijit/MovieX/tree/main/frontend/src/app">app</a>
    │       ├── <a href="https://github.com/ashavijit/MovieX/tree/main/frontend/src/components">components/</a>
    │       │   └── <a href="https://github.com/ashavijit/MovieX/tree/main/frontend/src/components/proto">proto</a>
    │       └── <a href="https://github.com/ashavijit/MovieX/tree/main/frontend/src/features">features/</a>
    │           ├── <a href="https://github.com/ashavijit/MovieX/tree/main/frontend/src/features/movie">movie</a>
    │           └── <a href="https://github.com/ashavijit/MovieX/tree/main/frontend/src/features/user">user</a>
    ├── <a href="https://github.com/ashavijit/MovieX/tree/main/login">Login</a>
    ├── <a href="https://github.com/ashavijit/MovieX/tree/main/movie">Movie/</a>
    │   └── <a href="https://github.com/ashavijit/MovieX/tree/main/movie/MovieData">MovieData/</a>
    │       ├── <a href="https://github.com/ashavijit/MovieX/tree/main/movie/MovieData/public">public/</a>
    │       │   └── <a href="https://github.com/ashavijit/MovieX/tree/main/movie/MovieData/public/images">images</a>
    │       └── <a href="https://github.com/ashavijit/MovieX/tree/main/movie/MovieData/src">src</a>
    ├── <a href="https://github.com/ashavijit/MovieX/tree/main/protobuf">Protobuf</a>
    ├── <a href="https://github.com/ashavijit/MovieX/tree/main/screenshots">Screenshots</a>
    ├── <a href="https://github.com/ashavijit/MovieX/tree/main/search">Search</a>
    ├── <a href="https://github.com/ashavijit/MovieX/tree/main/signup">Signup</a>
    └── <a href="https://github.com/ashavijit/MovieX/tree/main/updateUser">UpdateUser</a>
</pre>

## License

MovieX (MovieTicketReservation) is licensed under the MIT License.

[![GitHub license](https://img.shields.io/github/license/ashavijit/MovieX)](https://github.com/ashavijit/MovieX/blob/main/LICENCE)

## Contributors

<a href="https://github.com/ashavijit/MovieX/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ashavijit/MovieX" />
</a>

