<h1 align="center"> Mikan </h1> <br>

<p align="center">
  <a href="https://initiate.host/">
    <img alt="Mikan" title="Mikan" src="https://vgy.me/shLDxh.png" style="width: 200px;">
  </a>
</p>

<p align="center">
  Endpoint for MyAnimeList API (WIP)
</p>    

## Table of Contents

- [Introduction](#introduction)
- [Usage](#usage)
- [Issues](#issues)


## Introduction

Get a full MyAnimeList information on any kind of anime and manga (WIP) using their respective MAL ID.  
Made for our new soon-to-be-released app Setsuna and for future projects.  
 
It is **free** and has no limits of now _(30/12/2017)_

Example: [https://myanimelist.net/anime/1535/Death_Note](https://myanimelist.net/anime/1535/Death_Note), in this case the MAL ID is 1535. Check Usage to see how to interact with the API.
[https://i.imgur.com/FHExi6e.png](https://i.imgur.com/FHExi6e.png)

## Usage

Host:	[https://initiate.host/](https://initiate.host/)    

**JSON Rest Endpoints.**   

Normal Usage: /anime/{ID}  i.e.: [https://initiate.host/anime/1](https://initiate.host/anime/1)
  
For logs: /stratum/loggs/{ID}  
In case you want to filter the level, there's the parameter with 3 options called level:  
/stratum/loggs/{ID}?level={level}  
level can be error, debug or info

## Issues

Mikan is currently in development, do expect some little bugs (no missing data), and if you face any issue, open an issue with the request ID from the Json.
