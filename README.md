# spring-cloud-vault-sample
Sample application using spring-cloud-vault-config

## Getting started

Download and install spring-cloud-vault-config in local maven repo

    git clone git@github.com:singram/spring-cloud-vault-config.git
    cd spring-cloud-vault-config
    ./src/test/bash/install_vault.sh
    ./src/test/bash/create_certifications.sh
    ./src/test/bash/local_run_vault.sh
    ./mvnw install

Run vault in dev mode

   cd spring-cloud-vault-config
   ./vault/vault server -dev -dev-root-token-id="0000-0000-0000-0000"

To run the sample app

    git clone git@github.com:singram/spring-cloud-vault-sample.git
    cd spring-cloud-vault-sample
    ./gradlew clean bootRun
