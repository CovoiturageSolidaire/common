# Covoiturage Solidaire

## Generate backend and AngularX/React app
Install JHipster generator

```bash
git clone https://github.com/CovoiturageSolidaire/common.git
mkdir monolith
jhipster import-jdl ../common/model.jh
```

Run the backend
```bash
./mvnw
```

Run the frontend
```bash
yarn start
```


## Generate Ionic frontend
Install Ionic CLI
```bash
ionic start ionic4j oktadeveloper/jhipster
```
You can also install it using the [Ionic for JHipster Module](https://github.com/oktadeveloper/generator-jhipster-ionic):

```bash
npm install -g generator-jhipster-ionic
yo jhipster-ionic
```


```bash
cd app-ionic
yo jhipster-ionic:entity Place
yo jhipster-ionic:entity Person
yo jhipster-ionic:entity Car
yo jhipster-ionic:entity Driver
yo jhipster-ionic:entity Sponsor
yo jhipster-ionic:entity Request
```


```bash
ionic serve
```
