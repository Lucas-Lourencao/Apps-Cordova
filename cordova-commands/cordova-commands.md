# Cordova Commands

## Creating a new project:

> cordova create nameProject com.nameproject "Name App"

- cordova create → command to create the project;
- nameProject → project name, a folder with that name will be created for the project;
- com.nameproject → identificação do projeto para as lojas (Playstore / AppleStore), esse tem que ser único. Geralmente o endereço do site do seu app ao contrário;
- “Name App" → application name. We put it in double quotes because they are two separate words. CMD does not understand empty space.

## Checking available platforms:

> cordova platform lts

## Add platforms:

### Browser:

#### Add:

> cordova platform add browser

<p>This platform allows you to run the App in the browser</p>

#### Remove:

> cordova platform remove browser

#### Run:

> cordova run browser

### Android:

#### Add:

> cordova platform add android

#### Remove:

> cordova remove platform android

## Testing the project on mobile - debug.apk

> cordova build android

→ C:\Apps\nameProject\platforms\android\app\build\outputs\apk\debug

<p>Put the file app-debug.apk on the phone and test</p>
