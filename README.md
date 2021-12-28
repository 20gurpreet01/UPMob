# upMob
<p align="center">

![GitHub repo size](https://img.shields.io/github/repo-size/20gurpreet01/UPMob?style=for-the-badge)
![GitHub](https://img.shields.io/github/license/20gurpreet01/UPMob?style=for-the-badge)
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/20gurpreet01/UPMob?style=for-the-badge)
</p>

<p align="center">UpMob uses <a href="https://github.com/20gurpreet01/UPMob-api">UpMob API</a> to get the mobiles devices information which are yet to come to Indian markets<p>



## :rocket: Getting Started
1. <a href="https://flutter.dev/docs/get-started/install">**Install the Flutter SDK & Android Studio**</a>
2. Navigate into the project directory.
3. Define the environment variables in ```.env``` file at root of the project.
   ```.env
    API_HOST=yourhost.com
    API_PORT=8080
    API_PATH=/some-path
    ```

    You might like [rest-client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client), if you use [VS Code](https://code.visualstudio.com/). This extension  allows you to send HTTP request and view the response in VS Code directly. Rest-client API requests are already defined in the ```api_requests/``` directory. You need to define the environment vairables though. In the ```.vscode/settings.json```,
    ```
    {
        "rest-client.environmentVariables": {
            "$shared": {
                "API_HOST": "yourhost.com",
                "API_PORT": "8080",
                "API_PATH": "/some-path"
            }
        }
    }
    ```
4. Run 
    ```shell
    flutter run 
    ```
5. Open the code and start editing.

## :hammer: Uses UPMob API 
UpMob depends on [UPMob API](https://github.com/20gurpreet01/UPMob-API)

## :pencil2: TODO 
- [ ] Bookmark devices
- [ ] Toggle between Themes
- [ ] Locate Nearby Stores using Google Maps API 

## :memo: License
Licensed under the [MIT License](https://github.com/20gurpreet01/UPMob/blob/main/LICENSE). 

## :sparkles: Development and Contributing
Yes, please! Feel free to contribute, raise issues and recommend best practices.

A few resources to get you started:
- [Flutter Documentation](https://flutter.dev/docs)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)
