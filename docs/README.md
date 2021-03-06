<!--
Copyright 2017 - The RepoSeed-server authors
This work is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License;
you may not use this file except in compliance with the License.
You may obtain a copy of the License at
    https://creativecommons.org/licenses/by-sa/4.0/legalcode
Unless required by applicable law or agreed to in writing, documentation
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->


## Development
Run the following commands to install reposeed-server and change your directory to reposeed's source code directory.
```
go get -v -u github.com/okkur/reposeed-server
cd $GOPATH/src/github.com/okkur/reposeed-server
```

Rename .env.example to .env and change the values in the file.   
Then run the following command to install **packr**
```
make packr
```

In case you made any changes on templates run ```make``` or ```packr install .``` to bundle templates into the generated binary.
# Documentation

No documentation available yet. Start your first contribution with some documentation.

See how you can contribute with our [contribution guide](/CONTRIBUTING.md).
