# Supported tags and respective `Dockerfile` links

-	[`5.2.8`, `5.2`, `5`, `latest` (*5/Dockerfile*)](https://github.com/butter/docker-angular/blob/5d6a46b4f7e7080807002e7f928cbc4f95edf7ee/5/Dockerfile)
-	[`4.0.0`, `4.0`, `4` (*4/Dockerfile*)](https://github.com/butter/docker-angular/blob/f9efce93fb6e393f0d649d179533f5865ec9bc23/4/Dockerfile)
-	[`2.4.6`, `2.4`, `2` (*2/Dockerfile*)](https://github.com/butter/docker-angular/blob/f9efce93fb6e393f0d649d179533f5865ec9bc23/2/Dockerfile)
-	[`2.4.5` (*2/Dockerfile*)](https://github.com/butter/docker-angular/blob/c5af46c67b57ba8e5184bc4f769ade126902bd22/2/Dockerfile)

# What is Angular?
Angular (commonly referred to as "Angular 2+" or "Angular 2") is a TypeScript-based open-source front-end web application platform led by the Angular Team at Google and by a community of individuals and corporations to address all of the parts of the developer's workflow while building complex web applications. Angular is a complete rewrite from the same team that built AngularJS.

> [wikipedia.org/Angular\_(application_platform)](https://en.wikipedia.org/wiki/Angular_(application_platform))

![logo](https://upload.wikimedia.org/wikipedia/commons/c/cf/Angular_full_color_logo.svg)

# How to use this image

## Create a `Dockerfile` in your Angular project

```dockerfile
FROM butter/angular:5.2.8
CMD [ "npm", "start" ]
```

# License

View license information for [Angular](https://angular.io/license).
