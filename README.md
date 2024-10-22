# ADB Remote Translations

> [!NOTE]\
> This repository is only for contributing translations for the ADB Remote app. If you'd like to contribute translations or report bugs/feature requests related to the app, please refer to the guidelines below.

## Documentation & app download

Please visit ADB Remote website <https://adbremote.netlify.app>.

## Bug reports & feature requests

To submit a bug report or request a new feature for the ADB Remote app:

1. Navigate to the [Issues](https://github.com/kaungkhantjc/adb-remote-translations/issues) page.
2. Click on "New Issue".
3. Choose either "Bug report" or "Feature request."
4. Fill in the required details and submit your issue.

## Contributing

We appreciate any contributions to translations for ADB Remote! Follow the steps below to contribute:

1. Fork the repository to your GitHub account.
2. Create a new folder for the desired language by copying the `values` folder and renaming it with the appropriate language code suffix. For example,

    | Language  | Folder name |
    | ------------- | ------------- |
    | Burmese  | values-my  |
    | French  | values-fr  |
    | Russian  | values-ru  |

    For more information about ISO 639 language codes, please refer to [this](https://en.wikipedia.org/wiki/List_of_ISO_639_language_codes).

3. Translate the strings inside `strings.xml` and `arrays.xml` files in the newly created folder.

    > **IMPORTANT** : Delete every string marked with `translatable="false"`.

4. After completing your translations, submit a Pull Request (PR) with the changes.
5. Upon review and approval of the PR, the translations will be incorporated into a future update, **with contributors acknowledged in the credits section**.

Thank you for contributing to making ADB Remote better for users around the world!

## License

ADB Remote Translations is licensed under the Apache License 2.0.

```
Copyright 2024 ADB Remote Translations contributors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
