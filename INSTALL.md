# PLATAFORMA VIRTUAL DE TRÁMITES

## Requirements



## Install


```

* Clone the project

```sh
git clone https://github.com/MUTUAL-DE-SERVICIOS-AL-POLICIA/PVT.git
cd PVT
git fetch --tags
latestVersion=$(git describe --tags `git rev-list --tags --max-count=1`)
git checkout $latestVersion
```

* Install dependencies

```sh
composer run-script post-root-package-install
composer install
yarn
```

* Edit `.env` file with database credentials and established manteinance modes

* Generate keys and compile JS files

```sh
composer run-script post-create-project-cmd
yarn prod
```