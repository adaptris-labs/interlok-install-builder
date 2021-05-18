# interlok-install-builder

The suggested name was `urban-eureka`

Project assists in creating local installation of Interlok with optional dependencies.

## Usage

1. Update dependencies in `build.gradle`
2. Create `gradle.properties` containing `interlokInstallDirectory` (default: `./build/distribution`)

    ```properties
    interlokInstallDirectory=C:/Adaptris/Interlok
    ```

3. Execute gradle build:

    ```shell
    ./gradlew cleanInstall install
    ```
