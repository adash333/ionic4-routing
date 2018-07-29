# ionic4-routing

このページは、[Ionic 4/Angular Tutorial - Ionic 4 Router (Routing and Navigation Example)](https://www.techiediaries.com/ionic-4-angular-routing/)と、[How to integrate Firebase with Angular 6 – AngularFire2 V5](https://grokonez.com/frontend/angular/how-to-integrate-angular-6-firebase-tutorial-angularfire2-v5)を参考に、ionic4アプリ作成の練習を行っているものです。


src/environments/environment.ts は、ご自身のfirebaseのAPIキーその他をコピペしてください。

```javascript:environment.ts
// <>となっている部分は、自分のapiKeyを入力
export const environment = {
  production: false,
  firebase: {
    apiKey: '<your-key>',
    authDomain: '<your-project-authdomain>',
    databaseURL: '<your-database-URL>',
    projectId: '<your-project-id>',
    storageBucket: '<your-storage-bucket>',
    messagingSenderId: '<your-messaging-sender-id>'
  }
};
```

## インストール方法

`git clone https://github.com/adash333/ionic4-routing.git`

modify "src/environments/environment.ts"

Run `npm install`to install all dependencies.

Run `ionic serve`to start the development environment.

## 作成経過は以下に記載しています。

http://twosquirrel.mints.ne.jp/?p=26533  
Ionic4(beta)でルーティングとページ遷移
2018/7/28

http://twosquirrel.mints.ne.jp/?p=26596  
Ionic4(beta)でFirebase利用（AngularFire2@5.0.0-rc.11）
2018/7/28 2018/7/29 


## 開発環境

```
Windows 8.1 Pro
VisualStudioCode
git version 2.16.1.windows.4
Sourcetree Version 2.4.8.0
Android Studio 3.0.1

Node v8.11.2
npm 6.1.0
Ionic (Ionic CLI) 4.0.1
@ionic/angular 4.0.0-beta.0

typings@2.1.1
typescript@2.9.2
firebase@5.3.0
angularfire2@5.0.0-rc.11
```
