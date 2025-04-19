├── .gcloudignore
├── .github
    └── no-response.yaml
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE.txt
├── MANIFEST.in
├── README.md
├── SECURITY.md
├── docs
    ├── ApiBlobType.md
    ├── Collaborator.md
    ├── CreateInboxFileRequest.md
    ├── DatasetColumn.md
    ├── DatasetNewRequest.md
    ├── DatasetNewVersionRequest.md
    ├── DatasetUpdateSettingsRequest.md
    ├── Error.md
    ├── KaggleApi.md
    ├── KernelPushRequest.md
    ├── License.md
    ├── ModelInstanceNewVersionRequest.md
    ├── ModelInstanceUpdateRequest.md
    ├── ModelNewInstanceRequest.md
    ├── ModelNewRequest.md
    ├── ModelUpdateRequest.md
    ├── README.md
    ├── Result.md
    ├── StartBlobUploadRequest.md
    ├── StartBlobUploadResponse.md
    ├── UploadFile.md
    ├── conf.py
    ├── datasets_metadata.md
    ├── index.rst
    ├── kernels_metadata.md
    ├── model_card.md
    ├── modelinstance_usage.md
    └── models_metadata.md
├── integration_tests
    └── test_models.py
├── kaggle
    ├── LICENSE
    ├── __init__.py
    ├── api
    │   ├── __init__.py
    │   ├── kaggle_api.py
    │   └── kaggle_api_extended.py
    ├── cli.py
    ├── configuration.py
    ├── models
    │   ├── __init__.py
    │   ├── dataset_column.py
    │   ├── dataset_new_request.py
    │   ├── dataset_new_version_request.py
    │   ├── dataset_update_settings_request.py
    │   ├── kaggle_models_extended.py
    │   ├── kernel_push_request.py
    │   ├── model_instance_new_version_request.py
    │   ├── model_instance_update_request.py
    │   ├── model_new_instance_request.py
    │   ├── model_new_request.py
    │   ├── model_update_request.py
    │   ├── start_blob_upload_request.py
    │   ├── start_blob_upload_response.py
    │   └── upload_file.py
    └── test
    │   ├── __init__.py
    │   └── test_authenticate.py
├── kagglesdk
    ├── LICENSE
    ├── __init__.py
    ├── admin
    │   ├── __init__.py
    │   ├── services
    │   │   ├── __init__.py
    │   │   └── inbox_file_service.py
    │   └── types
    │   │   ├── __init__.py
    │   │   └── inbox_file_service.py
    ├── blobs
    │   ├── __init__.py
    │   ├── services
    │   │   ├── __init__.py
    │   │   └── blob_api_service.py
    │   └── types
    │   │   ├── __init__.py
    │   │   └── blob_api_service.py
    ├── common
    │   ├── __init__.py
    │   └── types
    │   │   ├── __init__.py
    │   │   ├── file_download.py
    │   │   └── http_redirect.py
    ├── competitions
    │   ├── __init__.py
    │   ├── services
    │   │   ├── __init__.py
    │   │   └── competition_api_service.py
    │   └── types
    │   │   ├── __init__.py
    │   │   ├── competition_api_service.py
    │   │   ├── competition_enums.py
    │   │   └── submission_status.py
    ├── datasets
    │   ├── __init__.py
    │   ├── services
    │   │   ├── __init__.py
    │   │   └── dataset_api_service.py
    │   └── types
    │   │   ├── __init__.py
    │   │   ├── dataset_api_service.py
    │   │   ├── dataset_enums.py
    │   │   └── dataset_types.py
    ├── education
    │   ├── __init__.py
    │   ├── services
    │   │   ├── __init__.py
    │   │   └── education_api_service.py
    │   └── types
    │   │   ├── __init__.py
    │   │   ├── education_api_service.py
    │   │   └── education_service.py
    ├── kaggle_client.py
    ├── kaggle_env.py
    ├── kaggle_http_client.py
    ├── kaggle_object.py
    ├── kernels
    │   ├── __init__.py
    │   ├── services
    │   │   ├── __init__.py
    │   │   └── kernels_api_service.py
    │   └── types
    │   │   ├── __init__.py
    │   │   ├── kernels_api_service.py
    │   │   └── kernels_enums.py
    ├── models
    │   ├── __init__.py
    │   ├── services
    │   │   ├── __init__.py
    │   │   ├── model_api_service.py
    │   │   └── model_service.py
    │   └── types
    │   │   ├── __init__.py
    │   │   ├── model_api_service.py
    │   │   ├── model_enums.py
    │   │   ├── model_service.py
    │   │   └── model_types.py
    ├── security
    │   ├── __init__.py
    │   ├── services
    │   │   ├── __init__.py
    │   │   └── oauth_service.py
    │   └── types
    │   │   ├── __init__.py
    │   │   ├── authentication.py
    │   │   └── oauth_service.py
    ├── test
    │   └── test_client.py
    └── users
    │   ├── __init__.py
    │   ├── services
    │       ├── __init__.py
    │       └── account_service.py
    │   └── types
    │       ├── __init__.py
    │       ├── account_service.py
    │       └── users_enums.py
├── pyproject.toml
├── requirements.in
├── requirements.txt
├── setup.cfg
├── setup.py
├── src
    ├── __init__.py
    ├── kaggle
    │   ├── LICENSE
    │   ├── __init__.py
    │   ├── api
    │   │   ├── __init__.py
    │   │   ├── kaggle_api.py
    │   │   └── kaggle_api_extended.py
    │   ├── cli.py
    │   ├── configuration.py
    │   ├── models
    │   │   ├── __init__.py
    │   │   ├── api_blob_type.py
    │   │   ├── dataset_column.py
    │   │   ├── dataset_new_request.py
    │   │   ├── dataset_new_version_request.py
    │   │   ├── dataset_update_settings_request.py
    │   │   ├── kaggle_models_extended.py
    │   │   ├── kernel_push_request.py
    │   │   ├── model_instance_new_version_request.py
    │   │   ├── model_instance_update_request.py
    │   │   ├── model_new_instance_request.py
    │   │   ├── model_new_request.py
    │   │   ├── model_update_request.py
    │   │   ├── start_blob_upload_request.py
    │   │   ├── start_blob_upload_response.py
    │   │   └── upload_file.py
    │   └── test
    │   │   ├── __init__.py
    │   │   └── test_authenticate.py
    ├── kagglesdk
    │   ├── LICENSE
    │   ├── __init__.py
    │   ├── admin
    │   │   ├── __init__.py
    │   │   ├── services
    │   │   │   ├── __init__.py
    │   │   │   └── inbox_file_service.py
    │   │   └── types
    │   │   │   ├── __init__.py
    │   │   │   └── inbox_file_service.py
    │   ├── blobs
    │   │   ├── __init__.py
    │   │   ├── services
    │   │   │   ├── __init__.py
    │   │   │   └── blob_api_service.py
    │   │   └── types
    │   │   │   ├── __init__.py
    │   │   │   └── blob_api_service.py
    │   ├── common
    │   │   ├── __init__.py
    │   │   └── types
    │   │   │   ├── __init__.py
    │   │   │   ├── file_download.py
    │   │   │   └── http_redirect.py
    │   ├── competitions
    │   │   ├── __init__.py
    │   │   ├── services
    │   │   │   ├── __init__.py
    │   │   │   └── competition_api_service.py
    │   │   └── types
    │   │   │   ├── __init__.py
    │   │   │   ├── competition_api_service.py
    │   │   │   ├── competition_enums.py
    │   │   │   └── submission_status.py
    │   ├── datasets
    │   │   ├── __init__.py
    │   │   ├── services
    │   │   │   ├── __init__.py
    │   │   │   └── dataset_api_service.py
    │   │   └── types
    │   │   │   ├── __init__.py
    │   │   │   ├── dataset_api_service.py
    │   │   │   ├── dataset_enums.py
    │   │   │   └── dataset_types.py
    │   ├── education
    │   │   ├── __init__.py
    │   │   ├── services
    │   │   │   ├── __init__.py
    │   │   │   └── education_api_service.py
    │   │   └── types
    │   │   │   ├── __init__.py
    │   │   │   ├── education_api_service.py
    │   │   │   └── education_service.py
    │   ├── kaggle_client.py
    │   ├── kaggle_env.py
    │   ├── kaggle_http_client.py
    │   ├── kaggle_object.py
    │   ├── kernels
    │   │   ├── __init__.py
    │   │   ├── services
    │   │   │   ├── __init__.py
    │   │   │   └── kernels_api_service.py
    │   │   └── types
    │   │   │   ├── __init__.py
    │   │   │   ├── kernels_api_service.py
    │   │   │   └── kernels_enums.py
    │   ├── models
    │   │   ├── __init__.py
    │   │   ├── services
    │   │   │   ├── __init__.py
    │   │   │   ├── model_api_service.py
    │   │   │   └── model_service.py
    │   │   └── types
    │   │   │   ├── __init__.py
    │   │   │   ├── model_api_service.py
    │   │   │   ├── model_enums.py
    │   │   │   ├── model_service.py
    │   │   │   └── model_types.py
    │   ├── security
    │   │   ├── __init__.py
    │   │   ├── services
    │   │   │   ├── __init__.py
    │   │   │   └── oauth_service.py
    │   │   └── types
    │   │   │   ├── __init__.py
    │   │   │   ├── authentication.py
    │   │   │   └── oauth_service.py
    │   ├── test
    │   │   └── test_client.py
    │   └── users
    │   │   ├── __init__.py
    │   │   ├── services
    │   │       ├── __init__.py
    │   │       └── account_service.py
    │   │   └── types
    │   │       ├── __init__.py
    │   │       ├── account_service.py
    │   │       └── users_enums.py
    ├── setup.cfg
    └── setup.py
├── tests
    ├── dataset
    │   └── data.csv
    ├── kernel
    │   └── testing.ipynb
    ├── model
    │   └── instance
    │   │   ├── data.csv
    │   │   └── version
    │   │       └── metadata.json
    ├── sample_submission.csv
    ├── test_commands.sh
    └── unit_tests.py
└── tools
    ├── GeneratePythonLibrary.sh
    ├── cicd
        └── integration-tests.yaml
    ├── releases
        ├── Dockerfile
        ├── cloudbuild.yaml
        ├── requirements.in
        └── requirements.txt
    ├── use-localhost.sh
    └── use-prod.sh


/.gcloudignore:
--------------------------------------------------------------------------------
1 | python


--------------------------------------------------------------------------------
/.github/no-response.yaml:
--------------------------------------------------------------------------------
 1 | name: No Response
 2 | 
 3 | # Both `issue_comment` and `scheduled` event types are required for this Action
 4 | # to work properly.
 5 | on:
 6 |   issue_comment:
 7 |     types: [created]
 8 |   schedule:
 9 |     # Schedule for five minutes after midnight, every day
10 |     - cron: '5 0 * * *'
11 | 
12 | # By specifying the access of one of the scopes, all of those that are not
13 | # specified are set to 'none'.
14 | permissions:
15 |   issues: write
16 | 
17 | jobs:
18 |   noResponse:
19 |     runs-on: ubuntu-latest
20 |     steps:
21 |       - uses: lee-dohm/no-response@9bb0a4b5e6a45046f00353d5de7d90fb8bd773bb
22 |         with:
23 |           token: ${{ github.token }}
24 |           # Comment to post when closing an Issue for lack of response. Set to `false` to disable
25 |           closeComment: >
26 |             Without additional information we're not able to resolve this issue,
27 |             so it will be closed at this time. You're still free to add more info
28 |             and respond to any questions above, though. We'll reopen the case
29 |             if you do. Thanks for your contribution!
30 |           # Number of days of inactivity before an issue is closed for lack of response.
31 |           daysUntilClose: 14
32 |           # Label requiring a response.
33 |           responseRequiredLabel: "waiting for response"


--------------------------------------------------------------------------------
/.gitignore:
--------------------------------------------------------------------------------
 1 | # Byte-compiled / optimized / DLL files
 2 | __pycache__/
 3 | *.py[cod]
 4 | *$py.class
 5 | 
 6 | # C extensions
 7 | *.so
 8 | 
 9 | # Distribution / packaging
10 | .Python
11 | env/
12 | build/
13 | develop-eggs/
14 | dist/
15 | downloads/
16 | eggs/
17 | .eggs/
18 | lib/
19 | lib64/
20 | parts/
21 | sdist/
22 | var/
23 | *.egg-info/
24 | .installed.cfg
25 | *.egg
26 | 
27 | # PyInstaller
28 | #  Usually these files are written by a python script from a template
29 | #  before PyInstaller builds the exe, so as to inject date/other infos into it.
30 | *.manifest
31 | *.spec
32 | 
33 | # Installer logs
34 | pip-log.txt
35 | pip-delete-this-directory.txt
36 | 
37 | # Unit test / coverage reports
38 | htmlcov/
39 | .tox/
40 | .coverage
41 | .coverage.*
42 | .cache
43 | nosetests.xml
44 | coverage.xml
45 | *,cover
46 | .hypothesis/
47 | venv/
48 | .python-version
49 | 
50 | # Translations
51 | *.mo
52 | *.pot
53 | 
54 | # Django stuff:
55 | *.log
56 | 
57 | # Sphinx documentation
58 | docs/_build/
59 | 
60 | # PyBuilder
61 | target/
62 | 
63 | #Ipython Notebook
64 | .ipynb_checkpoints
65 | 
66 | # Rider/IntelliJ
67 | .idea/
68 | 


--------------------------------------------------------------------------------
/CONTRIBUTING.md:
--------------------------------------------------------------------------------
 1 | # How to Contribute
 2 | 
 3 | We'd love to accept your patches and contributions to this project. There are
 4 | just a few small guidelines you need to follow.
 5 | 
 6 | ## Contributor License Agreement
 7 | 
 8 | Contributions to this project must be accompanied by a Contributor License
 9 | Agreement. You (or your employer) retain the copyright to your contribution;
10 | this simply gives us permission to use and redistribute your contributions as
11 | part of the project. Head over to <https://cla.developers.google.com/> to see
12 | your current agreements on file or to sign a new one.
13 | 
14 | You generally only need to submit a CLA once, so if you've already submitted one
15 | (even if it was for a different project), you probably don't need to do it
16 | again.
17 | 
18 | ## Code reviews
19 | 
20 | All submissions, including submissions by project members, require review. We
21 | use GitHub pull requests for this purpose. Consult
22 | [GitHub Help](https://help.github.com/articles/about-pull-requests/) for more
23 | information on using pull requests.
24 | 
25 | ## Community Guidelines
26 | 
27 | This project follows [Google's Open Source Community
28 | Guidelines](https://opensource.google.com/conduct/).


--------------------------------------------------------------------------------
/MANIFEST.in:
--------------------------------------------------------------------------------
1 | include LICENSE.txt


--------------------------------------------------------------------------------
/README.md:
--------------------------------------------------------------------------------
  1 | # Kaggle API
  2 | 
  3 | Official API for https://www.kaggle.com, accessible using a command line tool implemented in Python 3.  
  4 | 
  5 | [User documentation](docs/README.md)
  6 | 
  7 | ## Installation
  8 | 
  9 | Ensure you have Python 3 and the package manager `pip` installed.
 10 | 
 11 | Run the following command to access the Kaggle API using the command line:
 12 | 
 13 | ```sh
 14 | pip install kaggle
 15 | ```
 16 | 
 17 | ## Development
 18 | 
 19 | ### Kaggle Internal
 20 | 
 21 | Obviously, this depends on Kaggle services. When you're extending the API and modifying
 22 | or adding to those services, you should be working in your Kaggle mid-tier development
 23 | environment. You'll run Kaggle locally, in the container, and test the Python code by
 24 | running it in the container so it can connect to your local testing environment.
 25 | 
 26 | Also, run the following command to get `autogen.sh` installed:
 27 | ```bash
 28 | rm -rf /tmp/autogen && mkdir -p /tmp/autogen && unzip -qo /tmp/autogen.zip -d /tmp/autogen &&
 29 | mv /tmp/autogen/autogen-*/* /tmp/autogen && rm -rf /tmp/autogen/autogen-* &&
 30 | sudo chmod a+rx /tmp/autogen/autogen.sh
 31 | ```
 32 | 
 33 | ### Prerequisites
 34 | 
 35 | We use [hatch](https://hatch.pypa.io) to manage this project.
 36 | 
 37 | Follow these [instructions](https://hatch.pypa.io/latest/install/) to install it.
 38 | 
 39 | If you are working in a managed environment, you may want to use `pipx`. If it isn't already installed
 40 | try `sudo apt install pipx`. Then you should be able to proceed with `pipx install hatch`.
 41 | 
 42 | ### Dependencies
 43 | 
 44 | ```sh
 45 | hatch run install-deps
 46 | ```
 47 | 
 48 | ### Compile
 49 | 
 50 | ```sh
 51 | hatch run compile
 52 | ```
 53 | 
 54 | The compiled files are generated in the `kaggle/` directory from the `src/` directory.
 55 | 
 56 | All the changes must be done in the `src/` directory.
 57 | 
 58 | ### Run
 59 | 
 60 | You can also run the code in python directly:
 61 | 
 62 | ```sh
 63 | hatch run python
 64 | ```
 65 | 
 66 | ```python
 67 | import kaggle
 68 | from kaggle.api.kaggle_api_extended import KaggleApi
 69 | api = KaggleApi()
 70 | api.authenticate()
 71 | api.model_list_cli()
 72 | 
 73 | Next Page Token = [...]
 74 | [...]
 75 | 
 76 | ```
 77 | 
 78 | Or in a single command:
 79 | 
 80 | ```sh
 81 | hatch run python -c "import kaggle; from kaggle.api.kaggle_api_extended import KaggleApi; api = KaggleApi(); api.authenticate(); api.model_list_cli()"
 82 | ```
 83 | 
 84 | ### Example
 85 | 
 86 | Let's change the `model_list_cli` method in the source file: 
 87 | 
 88 | ```sh
 89 | ❯ git diff src/kaggle/api/kaggle_api_extended.py
 90 | [...]
 91 | +        print('hello Kaggle CLI update')^M
 92 |          models = self.model_list(sort_by, search, owner, page_size, page_token)
 93 | [...]
 94 | 
 95 | ❯ hatch run compile
 96 | [...]
 97 | 
 98 | ❯ hatch run python -c "import kaggle; from kaggle.api.kaggle_api_extended import KaggleApi; api = KaggleApi(); api.authenticate(); api.model_list_cli()"
 99 | hello Kaggle CLI update
100 | Next Page Token = [...]
101 | ```
102 | 
103 | ### Integration Tests
104 | 
105 | To run integration tests on your local machine, you need to set up your Kaggle API credentials. You can do this in one of these two ways described [this doc](docs/README.md). Refer to the sections: 
106 | - Using environment variables
107 | - Using credentials file
108 | 
109 | After setting up your credentials by any of these methods, you can run the integration tests as follows:
110 | 
111 | ```sh
112 | # Run all tests
113 | hatch run integration-test
114 | ```
115 | 
116 | ## License
117 | 
118 | The Kaggle API is released under the [Apache 2.0 license](LICENSE).
119 | 


--------------------------------------------------------------------------------
/SECURITY.md:
--------------------------------------------------------------------------------
 1 | # Security Policy
 2 | 
 3 | ## Supported Versions
 4 | 
 5 | Security updates are applied only to the latest release.
 6 | 
 7 | ## Reporting a Vulnerability
 8 | 
 9 | If you have discovered a security vulnerability in this project, please report it privately. **Do not disclose it as a public issue.** This gives us time to work with you to fix the issue before public exposure, reducing the chance that the exploit will be used before a patch is released.
10 | 
11 | Please disclose it at [security advisory](https://github.com/Kaggle/kaggle-api/security/advisories/new).
12 | 
13 | The vulnerabilities will be addressed as soon as possible, with a maximum of 90 days before a public exposure.
14 | 


--------------------------------------------------------------------------------
/docs/ApiBlobType.md:
--------------------------------------------------------------------------------
 1 | # ApiBlobType
 2 | 
 3 | ## Properties
 4 | Name | Type | Description | Notes
 5 | ------------ | ------------- | ------------- | -------------
 6 | 
 7 | [[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
 8 | 
 9 | 
10 | 


--------------------------------------------------------------------------------
/docs/Collaborator.md:
--------------------------------------------------------------------------------
 1 | # Collaborator
 2 | 
 3 | ## Properties
 4 | Name | Type | Description | Notes
 5 | ------------ | ------------- | ------------- | -------------
 6 | **username** | **str** | Username of the collaborator | 
 7 | **role** | **str** | Role of the collaborator | 
 8 | 
 9 | [[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
10 | 
11 | 
12 | 


--------------------------------------------------------------------------------
/docs/CreateInboxFileRequest.md:
--------------------------------------------------------------------------------
 1 | # CreateInboxFileRequest
 2 | 
 3 | ## Properties
 4 | Name | Type | Description | Notes
 5 | ------------ | ------------- | ------------- | -------------
 6 | **virtual_directory** | **str** | Directory name used for tagging the uploaded file | 
 7 | **blob_file_token** | **str** | Token representing the uploaded file | 
 8 | 
 9 | [[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
10 | 
11 | 
12 | 


--------------------------------------------------------------------------------
/docs/DatasetColumn.md:
--------------------------------------------------------------------------------
 1 | # DatasetColumn
 2 | 
 3 | ## Properties
 4 | Name | Type | Description | Notes
 5 | ------------ | ------------- | ------------- | -------------
 6 | **order** | **float** | The order that the column comes in, 0-based. (The first column is 0, second is 1, etc.) | [optional] 
 7 | **name** | **str** | The column name | [optional] 
 8 | **type** | **str** | The type of all of the fields in the column. Please see the data types on https://github.com/Kaggle/kaggle-api/wiki/Dataset-Metadata | [optional] 
 9 | **original_type** | **str** | Used to store the original type of the column, which will be converted to Kaggle&#39;s types. For example, an &#x60;originalType&#x60; of &#x60;\&quot;integer\&quot;&#x60; would convert to a &#x60;type&#x60; of &#x60;\&quot;numeric\&quot;&#x60; | [optional] 
10 | **description** | **str** | The description of the column | [optional] 
11 | 
12 | [[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
13 | 
14 | 
15 | 


--------------------------------------------------------------------------------
/docs/DatasetNewRequest.md:
--------------------------------------------------------------------------------
 1 | # DatasetNewRequest
 2 | 
 3 | ## Properties
 4 | Name | Type | Description | Notes
 5 | ------------ | ------------- | ------------- | -------------
 6 | **title** | **str** | The title of the new dataset | 
 7 | **slug** | **str** | The slug that the dataset should be created with | [optional] 
 8 | **owner_slug** | **str** | The owner&#39;s username | [optional] 
 9 | **license_name** | **str** | The license that should be associated with the dataset | [optional] [default to 'unknown']
10 | **subtitle** | **str** | The subtitle to be set on the dataset | [optional] 
11 | **description** | **str** | The description to be set on the dataset | [optional] [default to '']
12 | **files** | [**list[UploadFile]**](UploadFile.md) | A list of files that should be associated with the dataset | 
13 | **is_private** | **bool** | Whether or not the dataset should be private | [optional] [default to True]
14 | **convert_to_csv** | **bool** | Whether or not a tabular dataset should be converted to csv | [optional] [default to True]
15 | **category_ids** | **list[str]** | A list of tag IDs to associated with the dataset | [optional] 
16 | 
17 | [[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
18 | 
19 | 
20 | 


--------------------------------------------------------------------------------
/docs/DatasetNewVersionRequest.md:
--------------------------------------------------------------------------------
 1 | # DatasetNewVersionRequest
 2 | 
 3 | ## Properties
 4 | Name | Type | Description | Notes
 5 | ------------ | ------------- | ------------- | -------------
 6 | **version_notes** | **str** | The version notes for the new dataset version | 
 7 | **subtitle** | **str** | The subtitle to set on the dataset | [optional] 
 8 | **description** | **str** | The description to set on the dataset | [optional] 
 9 | **files** | [**list[UploadFile]**](UploadFile.md) | A list of files that should be associated with the dataset | 
10 | **convert_to_csv** | **bool** | Whether or not a tabular dataset should be converted to csv | [optional] [default to True]
11 | **category_ids** | **list[str]** | A list of tag IDs to associated with the dataset | [optional] 
12 | **delete_old_versions** | **bool** | Whether or not all previous versions of the dataset should be deleted upon creating the new version | [optional] [default to False]
13 | 
14 | [[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
15 | 
16 | 
17 | 


--------------------------------------------------------------------------------
/docs/DatasetUpdateSettingsRequest.md:
--------------------------------------------------------------------------------
 1 | # DatasetUpdateSettingsRequest
 2 | 
 3 | ## Properties
 4 | Name | Type | Description | Notes
 5 | ------------ | ------------- | ------------- | -------------
 6 | **title** | **str** | Title of the dataset | [optional] 
 7 | **subtitle** | **str** | Subtitle of the dataset | [optional] 
 8 | **description** | **str** | Decription of the dataset | [optional] 
 9 | **is_private** | **bool** | Whether or not the dataset should be private | [optional] 
10 | **licenses** | **list[object]** | A list of licenses that apply to this dataset | [optional] 
11 | **keywords** | **list[str]** | A list of keywords that apply to this dataset | [optional] 
12 | **collaborators** | **list[object]** | A list of collaborators that may read or edit this dataset | [optional] 
13 | **data** | **list[object]** | A list containing metadata for each file in the dataset | [optional] 
14 | 
15 | [[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
16 | 
17 | 
18 | 


--------------------------------------------------------------------------------
/docs/Error.md:
--------------------------------------------------------------------------------
 1 | # Error
 2 | 
 3 | ## Properties
 4 | Name | Type | Description | Notes
 5 | ------------ | ------------- | ------------- | -------------
 6 | **code** | **int** | The server error code returned | [optional] 
 7 | **message** | **str** | The error message generated by the server | [optional] 
 8 | 
 9 | [[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
10 | 
11 | 
12 | 


--------------------------------------------------------------------------------
/docs/KernelPushRequest.md:
--------------------------------------------------------------------------------
 1 | # KernelPushRequest
 2 | 
 3 | ## Properties
 4 | Name | Type | Description | Notes
 5 | ------------ | ------------- | ------------- | -------------
 6 | **id** | **int** | The kernel&#39;s ID number. One of &#x60;id&#x60; and &#x60;slug&#x60; are required. If both are specified, &#x60;id&#x60; will be preferred | [optional] 
 7 | **slug** | **str** | The full slug of the kernel to push to, in the format &#x60;USERNAME/KERNEL-SLUG&#x60;. The kernel slug must be the title lowercased with dashes (&#x60;-&#x60;) replacing spaces. One of &#x60;id&#x60; and &#x60;slug&#x60; are required. If both are specified, &#x60;id&#x60; will be preferred | [optional] 
 8 | **new_title** | **str** | The title to be set on the kernel | [optional] 
 9 | **text** | **str** | The kernel&#39;s source code | 
10 | **language** | **str** | The language that the kernel is written in | 
11 | **kernel_type** | **str** | The type of kernel. Cannot be changed once the kernel has been created | 
12 | **is_private** | **bool** | Whether or not the kernel should be private | [optional] 
13 | **enable_gpu** | **bool** | Whether or not the kernel should run on a GPU | [optional] 
14 | **enable_tpu** | **bool** | Whether or not the kernel should run on a TPU | [optional] 
15 | **enable_internet** | **bool** | Whether or not the kernel should be able to access the internet | [optional] 
16 | **dataset_data_sources** | **list[str]** | A list of dataset data sources that the kernel should use. Each dataset is specified as &#x60;USERNAME/DATASET-SLUG&#x60; | [optional] 
17 | **competition_data_sources** | **list[str]** | A list of competition data sources that the kernel should use | [optional] 
18 | **kernel_data_sources** | **list[str]** | A list of kernel data sources that the kernel should use. Each dataset is specified as &#x60;USERNAME/KERNEL-SLUG&#x60; | [optional] 
19 | **model_data_sources** | **list[str]** | A list of model data sources that the kernel should use. Each model is specified as &#x60;USERNAME/MODEL-SLUG/FRAMEWORK/VARIATION-SLUG/VERSION-NUMBER&#x60; | [optional] 
20 | **category_ids** | **list[str]** | A list of tag IDs to associated with the kernel | [optional] 
21 | **docker_image_pinning_type** | **str** | Which docker image to use for executing new versions going forward. | [optional] 
22 | 
23 | [[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
24 | 
25 | 
26 | 


--------------------------------------------------------------------------------
/docs/License.md:
--------------------------------------------------------------------------------
 1 | # License
 2 | 
 3 | ## Properties
 4 | Name | Type | Description | Notes
 5 | ------------ | ------------- | ------------- | -------------
 6 | **name** | **str** | Name of the license | 
 7 | 
 8 | [[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
 9 | 
10 | 
11 | 


--------------------------------------------------------------------------------
/docs/ModelInstanceNewVersionRequest.md:
--------------------------------------------------------------------------------
 1 | # ModelInstanceNewVersionRequest
 2 | 
 3 | ## Properties
 4 | Name | Type | Description | Notes
 5 | ------------ | ------------- | ------------- | -------------
 6 | **version_notes** | **str** | The version notes for the model instance version | [optional] 
 7 | **files** | [**list[UploadFile]**](UploadFile.md) | A list of files that should be associated with the model instance version | 
 8 | 
 9 | [[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
10 | 
11 | 
12 | 


--------------------------------------------------------------------------------
/docs/ModelInstanceUpdateRequest.md:
--------------------------------------------------------------------------------
 1 | # ModelInstanceUpdateRequest
 2 | 
 3 | ## Properties
 4 | Name | Type | Description | Notes
 5 | ------------ | ------------- | ------------- | -------------
 6 | **overview** | **str** | The overview of the model instance (markdown) | [optional] 
 7 | **usage** | **str** | The description of how to use the model instance (markdown) | [optional] 
 8 | **license_name** | **str** | The license that should be associated with the model instance | [optional] [default to 'Apache 2.0']
 9 | **fine_tunable** | **bool** | Whether the model instance is fine tunable | [optional] [default to True]
10 | **training_data** | **list[str]** | A list of training data (urls or names) | [optional] 
11 | **model_instance_type** | **str** | Whether the model instance is a base model, external variant, internal variant, or unspecified | [optional] 
12 | **base_model_instance** | **str** | If this is an internal variant, the &#x60;{owner-slug}/{model-slug}/{framework}/{instance-slug}&#x60; of the base model instance | [optional] 
13 | **external_base_model_url** | **int** | If this is an external variant, a URL to the base model | [optional] 
14 | **update_mask** | **str** | Describes which fields to update | 
15 | 
16 | [[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
17 | 
18 | 
19 | 


--------------------------------------------------------------------------------
/docs/ModelNewInstanceRequest.md:
--------------------------------------------------------------------------------
 1 | # ModelNewInstanceRequest
 2 | 
 3 | ## Properties
 4 | Name | Type | Description | Notes
 5 | ------------ | ------------- | ------------- | -------------
 6 | **instance_slug** | **str** | The slug that the model instance should be created with | 
 7 | **framework** | **str** | The framework of the model instance | 
 8 | **overview** | **str** | The overview of the model instance (markdown) | [optional] 
 9 | **usage** | **str** | The description of how to use the model instance (markdown) | [optional] 
10 | **license_name** | **str** | The license that should be associated with the model instance | [default to 'Apache 2.0']
11 | **fine_tunable** | **bool** | Whether the model instance is fine tunable | [optional] [default to True]
12 | **training_data** | **list[str]** | A list of training data (urls or names) | [optional] 
13 | **model_instance_type** | **str** | Whether the model instance is a base model, external variant, internal variant, or unspecified | [optional] 
14 | **base_model_instance** | **str** | If this is an internal variant, the &#x60;{owner-slug}/{model-slug}/{framework}/{instance-slug}&#x60; of the base model instance | [optional] 
15 | **external_base_model_url** | **int** | If this is an external variant, a URL to the base model | [optional] 
16 | **files** | [**list[UploadFile]**](UploadFile.md) | A list of files that should be associated with the model instance version | [optional] 
17 | 
18 | [[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
19 | 
20 | 
21 | 


--------------------------------------------------------------------------------
/docs/ModelNewRequest.md:
--------------------------------------------------------------------------------
 1 | # ModelNewRequest
 2 | 
 3 | ## Properties
 4 | Name | Type | Description | Notes
 5 | ------------ | ------------- | ------------- | -------------
 6 | **owner_slug** | **str** | The owner&#39;s slug | 
 7 | **slug** | **str** | The slug that the model should be created with | 
 8 | **title** | **str** | The title of the new model | 
 9 | **subtitle** | **str** | The subtitle of the new model | [optional] 
10 | **is_private** | **bool** | Whether or not the model should be private | [default to True]
11 | **description** | **str** | The description to be set on the model | [optional] [default to '']
12 | **publish_time** | **date** | When the model was initially published | [optional] 
13 | **provenance_sources** | **str** | The provenance sources to be set on the model | [optional] [default to '']
14 | 
15 | [[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
16 | 
17 | 
18 | 


--------------------------------------------------------------------------------
/docs/ModelUpdateRequest.md:
--------------------------------------------------------------------------------
 1 | # ModelUpdateRequest
 2 | 
 3 | ## Properties
 4 | Name | Type | Description | Notes
 5 | ------------ | ------------- | ------------- | -------------
 6 | **title** | **str** | The title of the new model | [optional] 
 7 | **subtitle** | **str** | The subtitle of the new model | [optional] 
 8 | **is_private** | **bool** | Whether or not the model should be private | [optional] [default to True]
 9 | **description** | **str** | The description to be set on the model | [optional] [default to '']
10 | **publish_time** | **date** | When the model was initially published | [optional] 
11 | **provenance_sources** | **str** | The provenance sources to be set on the model | [optional] [default to '']
12 | **update_mask** | **str** | Describes which fields to update | [optional] 
13 | 
14 | [[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
15 | 
16 | 
17 | 


--------------------------------------------------------------------------------
/docs/Result.md:
--------------------------------------------------------------------------------
 1 | # Result
 2 | 
 3 | ## Properties
 4 | Name | Type | Description | Notes
 5 | ------------ | ------------- | ------------- | -------------
 6 | 
 7 | [[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
 8 | 
 9 | 
10 | 


--------------------------------------------------------------------------------
/docs/StartBlobUploadRequest.md:
--------------------------------------------------------------------------------
 1 | # StartBlobUploadRequest
 2 | 
 3 | ## Properties
 4 | Name | Type | Description | Notes
 5 | ------------ | ------------- | ------------- | -------------
 6 | **type** | **object** | The type of the blob (one of \&quot;dataset\&quot;, \&quot;model\&quot;, \&quot;inbox\&quot;) | [optional] 
 7 | **name** | **str** | Name of the file | 
 8 | **content_length** | **int** | Content length of the file in bytes | 
 9 | **content_type** | **str** | Content/MIME type (e.g. \&quot;text/plain\&quot;) of the file | [optional] 
10 | **last_modified_epoch_seconds** | **int** | Last modified date of file in seconds since epoch in UTC | [optional] 
11 | 
12 | [[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
13 | 
14 | 
15 | 


--------------------------------------------------------------------------------
/docs/StartBlobUploadResponse.md:
--------------------------------------------------------------------------------
 1 | # StartBlobUploadResponse
 2 | 
 3 | ## Properties
 4 | Name | Type | Description | Notes
 5 | ------------ | ------------- | ------------- | -------------
 6 | **token** | **str** | Opaque string token used to reference the new blob/file. | 
 7 | **create_url** | **str** | URL to use to start the upload. | 
 8 | 
 9 | [[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
10 | 
11 | 
12 | 


--------------------------------------------------------------------------------
/docs/UploadFile.md:
--------------------------------------------------------------------------------
 1 | # UploadFile
 2 | 
 3 | ## Properties
 4 | Name | Type | Description | Notes
 5 | ------------ | ------------- | ------------- | -------------
 6 | **token** | **str** | A token referencing a specific file upload that can be used across requests | [optional] 
 7 | **description** | **str** | The file description | [optional] 
 8 | **columns** | [**list[DatasetColumn]**](DatasetColumn.md) | A list of dataset column metadata | [optional] 
 9 | 
10 | [[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
11 | 
12 | 
13 | 


--------------------------------------------------------------------------------
/docs/conf.py:
--------------------------------------------------------------------------------
 1 | #!/usr/bin/python
 2 | #
 3 | # Copyright 2024 Kaggle Inc
 4 | #
 5 | # Licensed under the Apache License, Version 2.0 (the "License");
 6 | # you may not use this file except in compliance with the License.
 7 | # You may obtain a copy of the License at
 8 | #
 9 | #      http://www.apache.org/licenses/LICENSE-2.0
10 | #
11 | # Unless required by applicable law or agreed to in writing, software
12 | # distributed under the License is distributed on an "AS IS" BASIS,
13 | # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
14 | # See the License for the specific language governing permissions and
15 | # limitations under the License.
16 | 
17 | # Configuration file for the Sphinx documentation builder.
18 | #
19 | # This file only contains a selection of the most common options. For a full
20 | # list see the documentation:
21 | # https://www.sphinx-doc.org/en/master/usage/configuration.html
22 | 
23 | # -- Path setup --------------------------------------------------------------
24 | 
25 | # If extensions (or modules to document with autodoc) are in another directory,
26 | # add these directories to sys.path here. If the directory is relative to the
27 | # documentation root, use os.path.abspath to make it absolute, like shown here.
28 | 
29 | import os
30 | import sys
31 | 
32 | sys.path.insert(0, os.path.abspath('.'))
33 | 
34 | # -- Project information -----------------------------------------------------
35 | 
36 | project = 'kaggle'
37 | copyright = '2024, kaggle'
38 | author = 'kaggle'
39 | 
40 | # -- General configuration ---------------------------------------------------
41 | 
42 | # Add any Sphinx extension module names here, as strings. They can be
43 | # extensions coming with Sphinx (named 'sphinx.ext.*') or your custom
44 | # ones.
45 | extensions = ['sphinxarg.ext']
46 | 
47 | # Add any paths that contain templates here, relative to this directory.
48 | templates_path = ['_templates']
49 | 
50 | # List of patterns, relative to source directory, that match files and
51 | # directories to ignore when looking for source files.
52 | # This pattern also affects html_static_path and html_extra_path.
53 | exclude_patterns = ['_build', 'Thumbs.db', '.DS_Store']
54 | 
55 | # -- Options for HTML output -------------------------------------------------
56 | 
57 | # The theme to use for HTML and HTML Help pages.  See the documentation for
58 | # a list of builtin themes.
59 | #
60 | html_theme = 'alabaster'
61 | 
62 | # Add any paths that contain custom static files (such as style sheets) here,
63 | # relative to this directory. They are copied after the builtin static files,
64 | # so a file named "default.css" will overwrite the builtin "default.css".
65 | html_static_path = ['_static']
66 | 


--------------------------------------------------------------------------------
/docs/index.rst:
--------------------------------------------------------------------------------
1 | .. argparse::
2 |    :filename: extended/cli.py
3 |    :func: create_parser
4 |    :prog: kaggle
5 | 
6 | 


--------------------------------------------------------------------------------
/docs/kernels_metadata.md:
--------------------------------------------------------------------------------
 1 | To upload and run a kernel, a special `kernel-metadata.json` file must be specified. 
 2 | 
 3 | Here's a basic example for `kernel-metadata.json`:
 4 | ```
 5 | {
 6 |   "id": "timoboz/my-awesome-kernel",
 7 |   "id_no": 12345,
 8 |   "title": "My Awesome Kernel",
 9 |   "code_file": "my-awesome-kernel.ipynb",
10 |   "language": "python",
11 |   "kernel_type": "notebook",
12 |   "is_private": "false",
13 |   "enable_gpu": "false",
14 |   "enable_internet": "false",
15 |   "dataset_sources": ["timoboz/my-awesome-dataset"],
16 |   "competition_sources": [],
17 |   "kernel_sources": [],
18 |   "model_sources": []
19 | }
20 | ```
21 | You can also use the API command `kaggle kernels init -p /path/to/kernel` to have the API create this file for you for a new kernel. If you wish to get the metadata for an existing kernel, you can use `kaggle kernels pull -p /path/to/download -k username/kernel-slug -m`.
22 | 
23 | ## Contents
24 | We currently support the following metadata fields for kernels.
25 | * `id`: The URL slug of your kernel. One of `id` or `id_no` must be specified. If both are, `id_no` will be preferred.
26 |   1. Your username slug
27 |   2. A unique kernel slug
28 | * `id_no`: The kernel's numeric ID.  One of `id` or `id_no` must be specified. If both are, `id_no` will be preferred.
29 | * `title`: The title of the kernel. Required for new kernels - optional for existing ones. Please be aware that kernel titles and slugs are linked to each other. A kernel slug is always the title lowercased with dashes (`-`) replacing spaces. 
30 |   * If you wish to rename your kernel, you may change the title within the metadata. However, you will need to update the `id` as well AFTER the rename is complete.
31 | * `code_file`: The path to your kernel source code. Required. If not an absolute path, it should be relative to the location of `kernel-metadata.json`.
32 | * `language`: The language your kernel is written in. Valid options are `python`, `r`, and `rmarkdown`. Required.
33 | * `kernel_type`: The type of kernel. Valid options are `script` and `notebook`. Required.
34 | * `is_private`: Whether or not the kernel should be private. If not specified, will be `true`.
35 | * `enable_gpu`: Whether or not the kernel should run on a GPU. If not specified, will be `false`.
36 | * `enable_internet`: Whether or not the kernel should be able to access the internet. If not specified, will be `false`.
37 | * `dataset_sources`: A list of dataset sources, specified as `"username/dataset-slug"`
38 | * `competition_sources`: A list of competition sources, specified as `"competition-slug"`
39 | * `kernel_sources`: A list of kernel sources, specified as `"username/kernel-slug"`
40 | * `model_sources`: A list of model sources, specified as `"username/model-slug/framework/variation-slug/version-number"`
41 | 
42 | We will add further metadata processing in upcoming versions of the API.


--------------------------------------------------------------------------------
/docs/model_card.md:
--------------------------------------------------------------------------------
 1 | # Model Summary
 2 | 
 3 | Provide a brief overview of the model including details about its architecture, how it can be used, characteristics of the model, training data, and evaluation results.
 4 | 
 5 | ## Usage
 6 | 
 7 | How can this model be used? You should provide a code snippet that demonstrates how to load and/or fine-tune your model, and you should define the shape of both the inputs and the outputs.  Are there known and preventable failures to be aware of?
 8 | 
 9 | ## System
10 | 
11 | Is this a standalone model or part of a system? What are the input requirements? What are the downstream dependencies when using the model outputs?
12 | 
13 | ## Implementation requirements
14 | 
15 | What hardware and software were used for training the model? Describe the compute requirements for training and inference (e.g., # of chips, training time, total computation, measured performance, energy consumption).
16 | 
17 | # Model Characteristics
18 | 
19 | ## Model initialization
20 | 
21 | Was the model trained from scratch or fine-tuned from a pre-trained model?
22 | 
23 | ## Model stats
24 | 
25 | What’s the size of the model? Provide information about size, weights, layers, and latency.
26 | 
27 | ## Other details
28 | 
29 | Is the model pruned? Is it quantized? Describe any techniques to preserve differential privacy.
30 | 
31 | # Data Overview
32 | 
33 | Provide more details about the data used to train this model.
34 | 
35 | ## Training data
36 | 
37 | Describe the data that was used to train the model. How was it collected? What pre-processing was done?
38 | 
39 | ## Demographic groups
40 | 
41 | Describe any demographic data or attributes that suggest demographic groups
42 | 
43 | ## Evaluation data
44 | 
45 | What was the train / test / dev split? Are there notable differences between training and test data?
46 | 
47 | # Evaluation Results
48 | 
49 | ## Summary
50 | 
51 | Summarize and link to evaluation results for this analysis.
52 | 
53 | ## Subgroup evaluation results
54 | 
55 | Did you do any subgroup analysis? Describe the results and any assumptions about disaggregating data. Are there any known and preventable failures about this model?
56 | 
57 | ## Fairness 
58 | 
59 | How did you define fairness? What metrics and baselines did you use? What were the results of your analysis?
60 | 
61 | ## Usage limitations
62 | 
63 | Are there sensitive use cases? What factors might limit model performance and what conditions should be satisfied to use this model? 
64 | 
65 | ## Ethics
66 | 
67 | What ethical factors did the model developers consider? Were any risks identified? What mitigations or remediates were undertaken?
68 | 


--------------------------------------------------------------------------------
/docs/modelinstance_usage.md:
--------------------------------------------------------------------------------
 1 | # Model Format
 2 | 
 3 | Describe the format for the model (e.g. a SavedModel file for TF 2.0)
 4 | 
 5 | # Training Data
 6 | 
 7 | Describe the data that the model instance was trained on.
 8 | 
 9 | # Model Inputs
10 | 
11 | Describe the type and the shape of the model inputs.
12 | 
13 | # Model Outputs
14 | 
15 | Describe the type and the shape of the model outputs.
16 | 
17 | # Model Usage
18 | 
19 | Provide code snippets that demonstrate how to load and make use of the model instance.
20 | 
21 | # Fine-tuning
22 | 
23 | Provide code snippets that demonstrate how to fine-tune the model instance (if applicable).
24 | 
25 | # Changelog
26 | 
27 | Describe the differences between the different versions for this specific model instance (if applicable). 
28 | 


--------------------------------------------------------------------------------
/docs/models_metadata.md:
--------------------------------------------------------------------------------
  1 | A full model is composed of 3 types of entities:
  2 | 
  3 | 1. The model
  4 | 2. The instances
  5 | 3. The instance versions
  6 | 
  7 | Let's take the example of [efficientnet](https://www.kaggle.com/models/tensorflow/efficientnet) to explain these entities.
  8 | 
  9 | A model like `efficientnet` contains multiple instances.
 10 | 
 11 | An instance is a specific variation of the model (e.g. B0, B1, ...) with a certain framework (e.g. TensorFlow2).
 12 | 
 13 | ## Model
 14 | 
 15 | To create a model, a special `model-metadata.json` file must be specified. 
 16 | 
 17 | Here's a basic example for `model-metadata.json`:
 18 | ```
 19 | {
 20 |   "ownerSlug": "INSERT_OWNER_SLUG_HERE",
 21 |   "title": "INSERT_TITLE_HERE",
 22 |   "slug": "INSERT_SLUG_HERE",
 23 |   "subtitle": "",
 24 |   "isPrivate": true,
 25 |   "description": "Model Card Markdown, see below",
 26 |   "publishTime": "",
 27 |   "provenanceSources": ""
 28 | }
 29 | ```
 30 | 
 31 | You can also use the API command `kaggle models init -p /path/to/model` to have the API create this file for you for a new model. If you wish to get the metadata for an existing model, you can use `kaggle models get username/model-slug`.
 32 | 
 33 | ### Contents
 34 | 
 35 | We currently support the following metadata fields for models.
 36 | 
 37 | * `ownerSlug`: the slug of the user or organization
 38 | * `title`: the model's title
 39 | * `slug`: the model's slug (unique per owner)
 40 | * `licenseName`: the name of the license (see the list below)
 41 | * `subtitle`: the model's subtitle
 42 | * `isPrivate`: whether or not the model should be private (only visible by the owners). If not specified, will be `true`
 43 | * `description`: the model's card in markdown syntax (see the template below)
 44 | * `publishTime`: the original publishing time of the model
 45 | * `provenanceSources`: the provenance of the model
 46 | 
 47 | ### Description
 48 | 
 49 | You can find a template of the model card on this wiki page: https://github.com/Kaggle/kaggle-api/wiki/Model-Card
 50 | 
 51 | ## Model Instance
 52 | 
 53 | To create a model instance, a special `model-instance-metadata.json` file must be specified. 
 54 | 
 55 | Here's a basic example for `model-instance-metadata.json`:
 56 | ```
 57 | {
 58 |   "ownerSlug": "INSERT_OWNER_SLUG_HERE",
 59 |   "modelSlug": "INSERT_EXISTING_MODEL_SLUG_HERE",
 60 |   "instanceSlug": "INSERT_INSTANCE_SLUG_HERE",
 61 |   "framework": "INSERT_FRAMEWORK_HERE",
 62 |   "overview": "",
 63 |   "usage": "Usage Markdown, see below",
 64 |   "licenseName": "Apache 2.0",
 65 |   "fineTunable": False,
 66 |   "trainingData": [],
 67 |   "modelInstanceType": "Unspecified",
 68 |   "baseModelInstance": "",
 69 |   "externalBaseModelUrl": ""
 70 | }
 71 | ```
 72 | 
 73 | You can also use the API command `kaggle models instances init -p /path/to/model-instance` to have the API create this file for you for a new model instance.
 74 | 
 75 | ### Contents
 76 | 
 77 | We currently support the following metadata fields for model instances.
 78 | 
 79 | * `ownerSlug`: the slug of the user or organization of the model
 80 | * `modelSlug`: the existing model's slug
 81 | * `instanceSlug`: the slug of the instance
 82 | * `framework`: the instance's framework (possible options: `tensorFlow1`,`tensorFlow2`,`tfLite`,`tfJs`,`pyTorch`,`jax`,`coral`, ...)
 83 | * `overview`: a short overview of the instance
 84 | * `usage`: the instance's usage in markdown syntax (see the template below)
 85 | * `fineTunable`: whether the instance is fine tunable
 86 | * `trainingData`: a list of training data in the form of strings, URLs, Kaggle Datasets, etc...
 87 | * `modelInstanceType`: whether the model instance is a base model, external variant, internal variant, or unspecified
 88 | * `baseModelInstance`: if this is an internal variant, the `{owner-slug}/{model-slug}/{framework}/{instance-slug}` of the base model instance
 89 | * `externalBaseModelUrl`: if this is an external variant, a URL to the base model
 90 | 
 91 | ### Licenses
 92 | 
 93 | Here is a list of the available licenses for models:
 94 | 
 95 | - Apache 2.0
 96 | - Attribution 3.0 IGO (CC BY 3.0 IGO)
 97 | - Attribution 3.0 Unported (CC BY 3.0)
 98 | - Attribution 4.0 International (CC BY 4.0)
 99 | - Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0)
100 | - Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)
101 | - Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)
102 | - Attribution-NonCommercial-ShareAlike 3.0 IGO (CC BY-NC-SA 3.0 IGO)
103 | - BSD-3-Clause
104 | - CC BY-NC-SA 4.0
105 | - CC BY-SA 3.0
106 | - CC BY-SA 4.0
107 | - CC0: Public Domain
108 | - Community Data License Agreement - Permissive - Version 1.0
109 | - Community Data License Agreement - Sharing - Version 1.0
110 | - GNU Affero General Public License 3.0
111 | - GNU Free Documentation License 1.3
112 | - GNU Lesser General Public License 3.0
113 | - GPL 2
114 | - MIT
115 | - ODC Attribution License (ODC-By)
116 | - ODC Public Domain Dedication and Licence (PDDL)
117 | - GPL 3
118 | 
119 | ### Usage
120 | 
121 | You can find a template of the Usage markdown on this wiki page: https://github.com/Kaggle/kaggle-api/wiki/ModelInstance-Usage
122 | 
123 | The following template variables can be used in this markdown: 
124 | 
125 | - `${VERSION_NUMBER}` is replaced by the version number when rendered
126 | - `${VARIATION_SLUG}` is replaced by the variation slug when rendered
127 | - `${FRAMEWORK}` is replaced by the framework name
128 | - `${PATH}` is replaced by `/kaggle/input/<model_slug>/<framework>/<variation_slug>/<version>`.
129 | - `${FILEPATH}` is replaced by `/kaggle/input/<model_slug>/<framework>/<variation_slug>/<version>/<filename>`. This value is only defined if the databundle contain a single file
130 | - `${URL}` is replaced by the absolute URL of the model


--------------------------------------------------------------------------------
/integration_tests/test_models.py:
--------------------------------------------------------------------------------
 1 | import os
 2 | import unittest
 3 | from typing import List
 4 | 
 5 | from kaggle.api.kaggle_api_extended import KaggleApi
 6 | 
 7 | MODEL_HANDLE = "keras/bert"
 8 | MODEL_ID = 2819
 9 | 
10 | # TODO(messick) Add a test that creates a dataset w/o specifying privacy that is created private.
11 | 
12 | 
13 | class TestModels(unittest.TestCase):
14 |     def setUp(self):
15 |         self.api = KaggleApi()
16 |         self.api.authenticate()
17 | 
18 |     def test_list_models(self) -> None:
19 |         models = self.api.model_list()
20 |         self.assertGreater(len(models), 0)
21 | 
22 |     def test_get_model(self) -> None:
23 |         model = self.api.model_get(MODEL_HANDLE)
24 |         self.assertEqual(MODEL_ID, model.id)
25 | 


--------------------------------------------------------------------------------
/kaggle/__init__.py:
--------------------------------------------------------------------------------
1 | # coding=utf-8
2 | from __future__ import absolute_import
3 | from kaggle.api.kaggle_api_extended import KaggleApi
4 | 
5 | api = KaggleApi()
6 | api.authenticate()
7 | 


--------------------------------------------------------------------------------
/kaggle/api/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kaggle/api/__init__.py


--------------------------------------------------------------------------------
/kaggle/models/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kaggle/models/__init__.py


--------------------------------------------------------------------------------
/kaggle/models/model_instance_new_version_request.py:
--------------------------------------------------------------------------------
  1 | #!/usr/bin/python
  2 | #
  3 | # Copyright 2024 Kaggle Inc
  4 | #
  5 | # Licensed under the Apache License, Version 2.0 (the "License");
  6 | # you may not use this file except in compliance with the License.
  7 | # You may obtain a copy of the License at
  8 | #
  9 | #      http://www.apache.org/licenses/LICENSE-2.0
 10 | #
 11 | # Unless required by applicable law or agreed to in writing, software
 12 | # distributed under the License is distributed on an "AS IS" BASIS,
 13 | # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 14 | # See the License for the specific language governing permissions and
 15 | # limitations under the License.
 16 | 
 17 | # coding: utf-8
 18 | 
 19 | import pprint
 20 | import re  # noqa: F401
 21 | 
 22 | import six
 23 | 
 24 | from kaggle.models.upload_file import UploadFile  # noqa: F401,E501
 25 | 
 26 | 
 27 | class ModelInstanceNewVersionRequest(object):
 28 |     """
 29 |     Attributes:
 30 |       project_types (dict): The key is attribute name
 31 |                             and the value is attribute type.
 32 |       attribute_map (dict): The key is attribute name
 33 |                             and the value is json key in definition.
 34 |     """
 35 | 
 36 |     project_types = {'version_notes': 'str', 'files': 'list[UploadFile]'}
 37 | 
 38 |     attribute_map = {'version_notes': 'versionNotes', 'files': 'files'}
 39 | 
 40 |     def __init__(self, version_notes=None, files=None):  # noqa: E501
 41 | 
 42 |         self._version_notes = None
 43 |         self._files = None
 44 |         self.discriminator = None
 45 | 
 46 |         if version_notes is not None:
 47 |             self.version_notes = version_notes
 48 |         self.files = files
 49 | 
 50 |     @property
 51 |     def version_notes(self):
 52 |         """Gets the version_notes of this ModelInstanceNewVersionRequest.  #
 53 |         noqa: E501.
 54 | 
 55 |         The version notes for the model instance version  # noqa: E501
 56 | 
 57 |         :return: The version_notes of this
 58 |             ModelInstanceNewVersionRequest. # noqa: E501
 59 |         :rtype: str
 60 |         """
 61 |         return self._version_notes
 62 | 
 63 |     @version_notes.setter
 64 |     def version_notes(self, version_notes):
 65 |         """Sets the version_notes of this ModelInstanceNewVersionRequest.
 66 | 
 67 |         The version notes for the model instance version  # noqa: E501
 68 | 
 69 |         :param version_notes: The version_notes of this
 70 |             ModelInstanceNewVersionRequest. # noqa: E501
 71 |         :type: str
 72 |         """
 73 | 
 74 |         self._version_notes = version_notes
 75 | 
 76 |     @property
 77 |     def files(self):
 78 |         """Gets the files of this ModelInstanceNewVersionRequest.  # noqa:
 79 |         E501.
 80 | 
 81 |         A list of files that should be associated with the model
 82 |         instance version  # noqa: E501
 83 | 
 84 |         :return: The files of this ModelInstanceNewVersionRequest. #
 85 |             noqa: E501
 86 |         :rtype: list[UploadFile]
 87 |         """
 88 |         return self._files
 89 | 
 90 |     @files.setter
 91 |     def files(self, files):
 92 |         """Sets the files of this ModelInstanceNewVersionRequest.
 93 | 
 94 |         A list of files that should be associated with the model
 95 |         instance version  # noqa: E501
 96 | 
 97 |         :param files: The files of this ModelInstanceNewVersionRequest.
 98 |             # noqa: E501
 99 |         :type: list[UploadFile]
100 |         """
101 |         if files is None:
102 |             raise ValueError("Invalid value for `files`, must not be `None`")  # noqa: E501
103 | 
104 |         self._files = files
105 | 
106 |     def to_dict(self):
107 |         """Returns the model properties as a dict."""
108 |         result = {}
109 | 
110 |         for attr, _ in six.iteritems(self.project_types):
111 |             value = getattr(self, attr)
112 |             if isinstance(value, list):
113 |                 result[attr] = list(map(lambda x: x.to_dict() if hasattr(x, "to_dict") else x, value))
114 |             elif hasattr(value, "to_dict"):
115 |                 result[attr] = value.to_dict()
116 |             elif isinstance(value, dict):
117 |                 result[attr] = dict(
118 |                     map(
119 |                         lambda item: (item[0], item[1].to_dict()) if hasattr(item[1], "to_dict") else item,
120 |                         value.items(),
121 |                     )
122 |                 )
123 |             else:
124 |                 result[attr] = value
125 | 
126 |         return result
127 | 
128 |     def to_str(self):
129 |         """Returns the string representation of the model."""
130 |         return pprint.pformat(self.to_dict())
131 | 
132 |     def __repr__(self):
133 |         """For `print` and `pprint`"""
134 |         return self.to_str()
135 | 
136 |     def __eq__(self, other):
137 |         """Returns true if both objects are equal."""
138 |         if not isinstance(other, ModelInstanceNewVersionRequest):
139 |             return False
140 | 
141 |         return self.__dict__ == other.__dict__
142 | 
143 |     def __ne__(self, other):
144 |         """Returns true if both objects are not equal."""
145 |         return not self == other
146 | 


--------------------------------------------------------------------------------
/kaggle/models/start_blob_upload_response.py:
--------------------------------------------------------------------------------
  1 | #!/usr/bin/python
  2 | #
  3 | # Copyright 2024 Kaggle Inc
  4 | #
  5 | # Licensed under the Apache License, Version 2.0 (the "License");
  6 | # you may not use this file except in compliance with the License.
  7 | # You may obtain a copy of the License at
  8 | #
  9 | #      http://www.apache.org/licenses/LICENSE-2.0
 10 | #
 11 | # Unless required by applicable law or agreed to in writing, software
 12 | # distributed under the License is distributed on an "AS IS" BASIS,
 13 | # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 14 | # See the License for the specific language governing permissions and
 15 | # limitations under the License.
 16 | 
 17 | # coding: utf-8
 18 | 
 19 | import pprint
 20 | import re  # noqa: F401
 21 | 
 22 | import six
 23 | 
 24 | 
 25 | class StartBlobUploadResponse(object):
 26 |     """
 27 |     Attributes:
 28 |       project_types (dict): The key is attribute name
 29 |                             and the value is attribute type.
 30 |       attribute_map (dict): The key is attribute name
 31 |                             and the value is json key in definition.
 32 |     """
 33 | 
 34 |     project_types = {'token': 'str', 'create_url': 'str'}
 35 | 
 36 |     attribute_map = {'token': 'token', 'create_url': 'createUrl'}
 37 | 
 38 |     def __init__(self, token=None, create_url=None):  # noqa: E501
 39 |         """StartBlobUploadResponse - a model defined in Swagger"""  # noqa: E501
 40 | 
 41 |         self._token = None
 42 |         self._create_url = None
 43 |         self.discriminator = None
 44 | 
 45 |         self.token = token
 46 |         self.create_url = create_url
 47 | 
 48 |     @property
 49 |     def token(self):
 50 |         """Gets the token of this StartBlobUploadResponse.  # noqa: E501.
 51 | 
 52 |         Opaque string token used to reference the new blob/file.  # noqa:
 53 |         E501
 54 | 
 55 |         :return: The token of this StartBlobUploadResponse.  # noqa: E501
 56 |         :rtype: str
 57 |         """
 58 |         return self._token
 59 | 
 60 |     @token.setter
 61 |     def token(self, token):
 62 |         """Sets the token of this StartBlobUploadResponse.
 63 | 
 64 |         Opaque string token used to reference the new blob/file.  # noqa:
 65 |         E501
 66 | 
 67 |         :param token: The token of this StartBlobUploadResponse. # noqa:
 68 |             E501
 69 |         :type: str
 70 |         """
 71 |         if token is None:
 72 |             raise ValueError("Invalid value for `token`, must not be `None`")  # noqa: E501
 73 | 
 74 |         self._token = token
 75 | 
 76 |     @property
 77 |     def create_url(self):
 78 |         """Gets the create_url of this StartBlobUploadResponse.  # noqa: E501.
 79 | 
 80 |         URL to use to start the upload.  # noqa: E501
 81 | 
 82 |         :return: The create_url of this StartBlobUploadResponse. # noqa:
 83 |             E501
 84 |         :rtype: str
 85 |         """
 86 |         return self._create_url
 87 | 
 88 |     @create_url.setter
 89 |     def create_url(self, create_url):
 90 |         """Sets the create_url of this StartBlobUploadResponse.
 91 | 
 92 |         URL to use to start the upload.  # noqa: E501
 93 | 
 94 |         :param create_url: The create_url of this StartBlobUploadResponse. #
 95 |             noqa: E501
 96 |         :type: str
 97 |         """
 98 |         if create_url is None:
 99 |             raise ValueError("Invalid value for `create_url`, must not be `None`")  # noqa: E501
100 | 
101 |         self._create_url = create_url
102 | 
103 |     def to_dict(self):
104 |         """Returns the model properties as a dict."""
105 |         result = {}
106 | 
107 |         for attr, _ in six.iteritems(self.project_types):
108 |             value = getattr(self, attr)
109 |             if isinstance(value, list):
110 |                 result[attr] = list(map(lambda x: x.to_dict() if hasattr(x, "to_dict") else x, value))
111 |             elif hasattr(value, "to_dict"):
112 |                 result[attr] = value.to_dict()
113 |             elif isinstance(value, dict):
114 |                 result[attr] = dict(
115 |                     map(
116 |                         lambda item: (item[0], item[1].to_dict()) if hasattr(item[1], "to_dict") else item,
117 |                         value.items(),
118 |                     )
119 |                 )
120 |             else:
121 |                 result[attr] = value
122 | 
123 |         return result
124 | 
125 |     def to_str(self):
126 |         """Returns the string representation of the model."""
127 |         return pprint.pformat(self.to_dict())
128 | 
129 |     def __repr__(self):
130 |         """For `print` and `pprint`"""
131 |         return self.to_str()
132 | 
133 |     def __eq__(self, other):
134 |         """Returns true if both objects are equal."""
135 |         if not isinstance(other, StartBlobUploadResponse):
136 |             return False
137 | 
138 |         return self.__dict__ == other.__dict__
139 | 
140 |     def __ne__(self, other):
141 |         """Returns true if both objects are not equal."""
142 |         return not self == other
143 | 


--------------------------------------------------------------------------------
/kaggle/models/upload_file.py:
--------------------------------------------------------------------------------
  1 | #!/usr/bin/python
  2 | #
  3 | # Copyright 2024 Kaggle Inc
  4 | #
  5 | # Licensed under the Apache License, Version 2.0 (the "License");
  6 | # you may not use this file except in compliance with the License.
  7 | # You may obtain a copy of the License at
  8 | #
  9 | #      http://www.apache.org/licenses/LICENSE-2.0
 10 | #
 11 | # Unless required by applicable law or agreed to in writing, software
 12 | # distributed under the License is distributed on an "AS IS" BASIS,
 13 | # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 14 | # See the License for the specific language governing permissions and
 15 | # limitations under the License.
 16 | 
 17 | # coding: utf-8
 18 | 
 19 | import pprint
 20 | import re  # noqa: F401
 21 | 
 22 | import six
 23 | 
 24 | from kaggle.models.dataset_column import DatasetColumn  # noqa: F401,E501
 25 | 
 26 | 
 27 | class UploadFile(object):
 28 |     """
 29 |     Attributes:
 30 |       column_types (dict): The key is attribute name
 31 |                             and the value is attribute type.
 32 |       attribute_map (dict): The key is attribute name
 33 |                             and the value is json key in definition.
 34 |     """
 35 | 
 36 |     column_types = {'token': 'str', 'description': 'str', 'columns': 'list[DatasetColumn]'}
 37 | 
 38 |     attribute_map = {'token': 'token', 'description': 'description', 'columns': 'columns'}
 39 | 
 40 |     def __init__(self, token=None, description=None, columns=None):  # noqa: E501
 41 |         """UploadFile - a model defined in Swagger"""  # noqa: E501
 42 | 
 43 |         self._token = None
 44 |         self._description = None
 45 |         self._columns = None
 46 |         self.discriminator = None
 47 | 
 48 |         if token is not None:
 49 |             self.token = token
 50 |         if description is not None:
 51 |             self.description = description
 52 |         if columns is not None:
 53 |             self.columns = columns
 54 | 
 55 |     @property
 56 |     def token(self):
 57 |         """Gets the token of this UploadFile.  # noqa: E501.
 58 | 
 59 |         A token referencing a specific file upload that can be used across
 60 |         requests  # noqa: E501
 61 | 
 62 |         :return: The token of this UploadFile.  # noqa: E501
 63 |         :rtype: str
 64 |         """
 65 |         return self._token
 66 | 
 67 |     @token.setter
 68 |     def token(self, token):
 69 |         """Sets the token of this UploadFile.
 70 | 
 71 |         A token referencing a specific file upload that can be used across
 72 |         requests  # noqa: E501
 73 | 
 74 |         :param token: The token of this UploadFile.  # noqa: E501
 75 |         :type: str
 76 |         """
 77 | 
 78 |         self._token = token
 79 | 
 80 |     @property
 81 |     def description(self):
 82 |         """Gets the description of this UploadFile.  # noqa: E501.
 83 | 
 84 |         The file description  # noqa: E501
 85 | 
 86 |         :return: The description of this UploadFile.  # noqa: E501
 87 |         :rtype: str
 88 |         """
 89 |         return self._description
 90 | 
 91 |     @description.setter
 92 |     def description(self, description):
 93 |         """Sets the description of this UploadFile.
 94 | 
 95 |         The file description  # noqa: E501
 96 | 
 97 |         :param description: The description of this UploadFile. # noqa: E501
 98 |         :type: str
 99 |         """
100 | 
101 |         self._description = description
102 | 
103 |     @property
104 |     def columns(self):
105 |         """Gets the columns of this UploadFile.  # noqa: E501.
106 | 
107 |         A list of dataset column metadata  # noqa: E501
108 | 
109 |         :return: The columns of this UploadFile.  # noqa: E501
110 |         :rtype: list[DatasetColumn]
111 |         """
112 |         return self._columns
113 | 
114 |     @columns.setter
115 |     def columns(self, columns):
116 |         """Sets the columns of this UploadFile.
117 | 
118 |         A list of dataset column metadata  # noqa: E501
119 | 
120 |         :param columns: The columns of this UploadFile.  # noqa: E501
121 |         :type: list[DatasetColumn]
122 |         """
123 | 
124 |         self._columns = columns
125 | 
126 |     def to_dict(self):
127 |         """Returns the model properties as a dict."""
128 |         result = {}
129 | 
130 |         for attr, _ in six.iteritems(self.column_types):
131 |             value = getattr(self, attr)
132 |             if isinstance(value, list):
133 |                 result[attr] = list(map(lambda x: x.to_dict() if hasattr(x, "to_dict") else x, value))
134 |             elif hasattr(value, "to_dict"):
135 |                 result[attr] = value.to_dict()
136 |             elif isinstance(value, dict):
137 |                 result[attr] = dict(
138 |                     map(
139 |                         lambda item: (item[0], item[1].to_dict()) if hasattr(item[1], "to_dict") else item,
140 |                         value.items(),
141 |                     )
142 |                 )
143 |             else:
144 |                 result[attr] = value
145 | 
146 |         return result
147 | 
148 |     def to_str(self):
149 |         """Returns the string representation of the model."""
150 |         return pprint.pformat(self.to_dict())
151 | 
152 |     def __repr__(self):
153 |         """For `print` and `pprint`"""
154 |         return self.to_str()
155 | 
156 |     def __eq__(self, other):
157 |         """Returns true if both objects are equal."""
158 |         if not isinstance(other, UploadFile):
159 |             return False
160 | 
161 |         return self.__dict__ == other.__dict__
162 | 
163 |     def __ne__(self, other):
164 |         """Returns true if both objects are not equal."""
165 |         return not self == other
166 | 


--------------------------------------------------------------------------------
/kaggle/test/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kaggle/test/__init__.py


--------------------------------------------------------------------------------
/kaggle/test/test_authenticate.py:
--------------------------------------------------------------------------------
 1 | from kaggle.api.kaggle_api_extended import KaggleApi
 2 | 
 3 | # python -m unittest tests.test_authenticate
 4 | 
 5 | import os
 6 | import unittest
 7 | 
 8 | 
 9 | class TestAuthenticate(unittest.TestCase):
10 | 
11 |     def setUp(self):
12 |         print("setup             class:%s" % self)
13 | 
14 |     def tearDown(self):
15 |         print("teardown          class:TestStuff")
16 | 
17 |     # Environment
18 | 
19 |     def test_environment_variables(self):
20 |         os.environ['KAGGLE_USERNAME'] = 'dinosaur'
21 |         os.environ['KAGGLE_KEY'] = 'xxxxxxxxxxxx'
22 |         api = KaggleApi()
23 | 
24 |         # We haven't authenticated yet
25 |         self.assertTrue("key" not in api.config_values)
26 |         self.assertTrue("username" not in api.config_values)
27 |         api.authenticate()
28 | 
29 |         # Should be set from the environment
30 |         self.assertEqual(api.config_values['key'], 'xxxxxxxxxxxx')
31 |         self.assertEqual(api.config_values['username'], 'dinosaur')
32 | 
33 |     # Configuration Actions
34 | 
35 |     def test_config_actions(self):
36 |         api = KaggleApi()
37 | 
38 |         self.assertTrue(api.config_dir.endswith('kaggle'))
39 |         self.assertEqual(api.get_config_value('doesntexist'), None)
40 | 
41 | 
42 | if __name__ == '__main__':
43 |     unittest.main()
44 | 


--------------------------------------------------------------------------------
/kagglesdk/__init__.py:
--------------------------------------------------------------------------------
1 | from kagglesdk.kaggle_client import KaggleClient
2 | from kagglesdk.kaggle_env import KaggleEnv
3 | 


--------------------------------------------------------------------------------
/kagglesdk/admin/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/admin/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/admin/services/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/admin/services/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/admin/services/inbox_file_service.py:
--------------------------------------------------------------------------------
 1 | from kagglesdk.admin.types.inbox_file_service import CreateInboxFileRequest, CreateInboxFileResponse
 2 | from kagglesdk.kaggle_http_client import KaggleHttpClient
 3 | 
 4 | 
 5 | class InboxFileClient(object):
 6 |     """File drop/pickup functionality."""
 7 | 
 8 |     def __init__(self, client: KaggleHttpClient):
 9 |         self._client = client
10 | 
11 |     def create_inbox_file(self, request: CreateInboxFileRequest = None) -> CreateInboxFileResponse:
12 |         r"""
13 |         Creates (aka 'drops') a new file into the inbox.
14 | 
15 |         Args:
16 |           request (CreateInboxFileRequest):
17 |             The request object; initialized to empty instance if not specified.
18 |         """
19 | 
20 |         if request is None:
21 |             request = CreateInboxFileRequest()
22 | 
23 |         return self._client.call("admin.InboxFileService", "CreateInboxFile", request, CreateInboxFileResponse)
24 | 


--------------------------------------------------------------------------------
/kagglesdk/admin/types/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/admin/types/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/admin/types/inbox_file_service.py:
--------------------------------------------------------------------------------
 1 | from kagglesdk.kaggle_object import *
 2 | 
 3 | 
 4 | class CreateInboxFileRequest(KaggleObject):
 5 |     r"""
 6 |     Attributes:
 7 |       virtual_directory (str)
 8 |         Directory name used for tagging the uploaded file.
 9 |       blob_file_token (str)
10 |         Token representing the uploaded file.
11 |     """
12 | 
13 |     def __init__(self):
14 |         self._virtual_directory = ""
15 |         self._blob_file_token = ""
16 |         self._freeze()
17 | 
18 |     @property
19 |     def virtual_directory(self) -> str:
20 |         """Directory name used for tagging the uploaded file."""
21 |         return self._virtual_directory
22 | 
23 |     @virtual_directory.setter
24 |     def virtual_directory(self, virtual_directory: str):
25 |         if virtual_directory is None:
26 |             del self.virtual_directory
27 |             return
28 |         if not isinstance(virtual_directory, str):
29 |             raise TypeError('virtual_directory must be of type str')
30 |         self._virtual_directory = virtual_directory
31 | 
32 |     @property
33 |     def blob_file_token(self) -> str:
34 |         """Token representing the uploaded file."""
35 |         return self._blob_file_token
36 | 
37 |     @blob_file_token.setter
38 |     def blob_file_token(self, blob_file_token: str):
39 |         if blob_file_token is None:
40 |             del self.blob_file_token
41 |             return
42 |         if not isinstance(blob_file_token, str):
43 |             raise TypeError('blob_file_token must be of type str')
44 |         self._blob_file_token = blob_file_token
45 | 
46 |     def endpoint(self):
47 |         path = '/api/v1/inbox/files/create'
48 |         return path.format_map(self.to_field_map(self))
49 | 
50 |     @staticmethod
51 |     def method():
52 |         return 'POST'
53 | 
54 |     @staticmethod
55 |     def body_fields():
56 |         return '*'
57 | 
58 | 
59 | class CreateInboxFileResponse(KaggleObject):
60 |     r"""
61 |     NOTE: This is sent to non-admins, so we're intentionally *NOT* sending back
62 |     the full InboxFile (with its URL for a direct download).
63 | 
64 |     """
65 | 
66 |     pass
67 | 
68 | 
69 | CreateInboxFileRequest._fields = [
70 |     FieldMetadata("virtualDirectory", "virtual_directory", "_virtual_directory", str, "", PredefinedSerializer()),
71 |     FieldMetadata("blobFileToken", "blob_file_token", "_blob_file_token", str, "", PredefinedSerializer()),
72 | ]
73 | 
74 | CreateInboxFileResponse._fields = []
75 | 


--------------------------------------------------------------------------------
/kagglesdk/blobs/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/blobs/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/blobs/services/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/blobs/services/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/blobs/services/blob_api_service.py:
--------------------------------------------------------------------------------
 1 | from kagglesdk.blobs.types.blob_api_service import ApiStartBlobUploadRequest, ApiStartBlobUploadResponse
 2 | from kagglesdk.kaggle_http_client import KaggleHttpClient
 3 | 
 4 | 
 5 | class BlobApiClient(object):
 6 |     r"""
 7 |     Binary Large OBject (BLOB) service used for uploading files to Google Cloud
 8 |     Storage (GCS).
 9 |     """
10 | 
11 |     def __init__(self, client: KaggleHttpClient):
12 |         self._client = client
13 | 
14 |     def start_blob_upload(self, request: ApiStartBlobUploadRequest = None) -> ApiStartBlobUploadResponse:
15 |         r"""
16 |         Starts a blob upload (i.e. reserves a spot for the upload on GCS).
17 | 
18 |         Args:
19 |           request (ApiStartBlobUploadRequest):
20 |             The request object; initialized to empty instance if not specified.
21 |         """
22 | 
23 |         if request is None:
24 |             request = ApiStartBlobUploadRequest()
25 | 
26 |         return self._client.call("blobs.BlobApiService", "ApiStartBlobUpload", request, ApiStartBlobUploadResponse)
27 | 


--------------------------------------------------------------------------------
/kagglesdk/blobs/types/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/blobs/types/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/common/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/common/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/common/types/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/common/types/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/common/types/file_download.py:
--------------------------------------------------------------------------------
  1 | from kagglesdk.kaggle_object import *
  2 | from typing import Optional
  3 | 
  4 | 
  5 | class FileDownload(KaggleObject):
  6 |     r"""
  7 |     Standard response object representing a file download.
  8 |     See http://go/kaggle-proto-handler-file-downloads
  9 |     Some field names/descriptions borrowed from
 10 |     google3/gdata/rosy/proto/data.proto
 11 | 
 12 |     Attributes:
 13 |       content_type (str)
 14 |         MIME type of the data
 15 |         TODO(aip.dev/143): (-- api-linter: core::0143::standardized-codes=disabled
 16 |         --)
 17 |       file_name (str)
 18 |         Original file name
 19 |       token (str)
 20 |         A unique fingerprint for the file/media data
 21 |       content_length (int)
 22 |         Size of the data, in bytes (if known)
 23 |     """
 24 | 
 25 |     def __init__(self):
 26 |         self._content_type = ""
 27 |         self._file_name = ""
 28 |         self._token = ""
 29 |         self._content_length = None
 30 |         self._freeze()
 31 | 
 32 |     @property
 33 |     def content_type(self) -> str:
 34 |         r"""
 35 |         MIME type of the data
 36 |         TODO(aip.dev/143): (-- api-linter: core::0143::standardized-codes=disabled
 37 |         --)
 38 |         """
 39 |         return self._content_type
 40 | 
 41 |     @content_type.setter
 42 |     def content_type(self, content_type: str):
 43 |         if content_type is None:
 44 |             del self.content_type
 45 |             return
 46 |         if not isinstance(content_type, str):
 47 |             raise TypeError('content_type must be of type str')
 48 |         self._content_type = content_type
 49 | 
 50 |     @property
 51 |     def file_name(self) -> str:
 52 |         """Original file name"""
 53 |         return self._file_name
 54 | 
 55 |     @file_name.setter
 56 |     def file_name(self, file_name: str):
 57 |         if file_name is None:
 58 |             del self.file_name
 59 |             return
 60 |         if not isinstance(file_name, str):
 61 |             raise TypeError('file_name must be of type str')
 62 |         self._file_name = file_name
 63 | 
 64 |     @property
 65 |     def token(self) -> str:
 66 |         """A unique fingerprint for the file/media data"""
 67 |         return self._token
 68 | 
 69 |     @token.setter
 70 |     def token(self, token: str):
 71 |         if token is None:
 72 |             del self.token
 73 |             return
 74 |         if not isinstance(token, str):
 75 |             raise TypeError('token must be of type str')
 76 |         self._token = token
 77 | 
 78 |     @property
 79 |     def content_length(self) -> int:
 80 |         """Size of the data, in bytes (if known)"""
 81 |         return self._content_length or 0
 82 | 
 83 |     @content_length.setter
 84 |     def content_length(self, content_length: int):
 85 |         if content_length is None:
 86 |             del self.content_length
 87 |             return
 88 |         if not isinstance(content_length, int):
 89 |             raise TypeError('content_length must be of type int')
 90 |         self._content_length = content_length
 91 | 
 92 |     @classmethod
 93 |     def prepare_from(cls, http_response):
 94 |         return http_response
 95 | 
 96 | 
 97 | FileDownload._fields = [
 98 |     FieldMetadata("contentType", "content_type", "_content_type", str, "", PredefinedSerializer()),
 99 |     FieldMetadata("fileName", "file_name", "_file_name", str, "", PredefinedSerializer()),
100 |     FieldMetadata("token", "token", "_token", str, "", PredefinedSerializer()),
101 |     FieldMetadata(
102 |         "contentLength", "content_length", "_content_length", int, None, PredefinedSerializer(), optional=True
103 |     ),
104 | ]
105 | 


--------------------------------------------------------------------------------
/kagglesdk/common/types/http_redirect.py:
--------------------------------------------------------------------------------
  1 | from datetime import timedelta
  2 | from kagglesdk.kaggle_object import *
  3 | from typing import Optional
  4 | 
  5 | 
  6 | class HttpRedirect(KaggleObject):
  7 |     r"""
  8 |     Represents an HTTP redirect (e.g. 301 or 302) response.
  9 |     Patterned after ASP.NET MVC's RedirectResult.
 10 | 
 11 |     Attributes:
 12 |       url (str)
 13 |         Destination URL for the redirect.
 14 |       permanent (bool)
 15 |         Should it be an HTTP 301 (permanent) redirect or just temporary (HTTP
 16 |         302)?.
 17 |       bypass_encoding (bool)
 18 |         When `true`, the `url` is already encoded, so bypass `UriHelper.Encode`.
 19 |         Otherwise, invoke `UriHelper.Encode` on the `url` before returning to the
 20 |         client.
 21 |       expiry (timedelta)
 22 |         Specifies how long the redirected url can be cached.
 23 |     """
 24 | 
 25 |     def __init__(self):
 26 |         self._url = ""
 27 |         self._permanent = False
 28 |         self._bypass_encoding = None
 29 |         self._expiry = None
 30 |         self._freeze()
 31 | 
 32 |     @property
 33 |     def url(self) -> str:
 34 |         """Destination URL for the redirect."""
 35 |         return self._url
 36 | 
 37 |     @url.setter
 38 |     def url(self, url: str):
 39 |         if url is None:
 40 |             del self.url
 41 |             return
 42 |         if not isinstance(url, str):
 43 |             raise TypeError('url must be of type str')
 44 |         self._url = url
 45 | 
 46 |     @property
 47 |     def permanent(self) -> bool:
 48 |         r"""
 49 |         Should it be an HTTP 301 (permanent) redirect or just temporary (HTTP
 50 |         302)?.
 51 |         """
 52 |         return self._permanent
 53 | 
 54 |     @permanent.setter
 55 |     def permanent(self, permanent: bool):
 56 |         if permanent is None:
 57 |             del self.permanent
 58 |             return
 59 |         if not isinstance(permanent, bool):
 60 |             raise TypeError('permanent must be of type bool')
 61 |         self._permanent = permanent
 62 | 
 63 |     @property
 64 |     def bypass_encoding(self) -> bool:
 65 |         r"""
 66 |         When `true`, the `url` is already encoded, so bypass `UriHelper.Encode`.
 67 |         Otherwise, invoke `UriHelper.Encode` on the `url` before returning to the
 68 |         client.
 69 |         """
 70 |         return self._bypass_encoding or False
 71 | 
 72 |     @bypass_encoding.setter
 73 |     def bypass_encoding(self, bypass_encoding: bool):
 74 |         if bypass_encoding is None:
 75 |             del self.bypass_encoding
 76 |             return
 77 |         if not isinstance(bypass_encoding, bool):
 78 |             raise TypeError('bypass_encoding must be of type bool')
 79 |         self._bypass_encoding = bypass_encoding
 80 | 
 81 |     @property
 82 |     def expiry(self) -> timedelta:
 83 |         """Specifies how long the redirected url can be cached."""
 84 |         return self._expiry
 85 | 
 86 |     @expiry.setter
 87 |     def expiry(self, expiry: timedelta):
 88 |         if expiry is None:
 89 |             del self.expiry
 90 |             return
 91 |         if not isinstance(expiry, timedelta):
 92 |             raise TypeError('expiry must be of type timedelta')
 93 |         self._expiry = expiry
 94 | 
 95 |     @classmethod
 96 |     def prepare_from(cls, http_response):
 97 |         return http_response
 98 | 
 99 | 
100 | HttpRedirect._fields = [
101 |     FieldMetadata("url", "url", "_url", str, "", PredefinedSerializer()),
102 |     FieldMetadata("permanent", "permanent", "_permanent", bool, False, PredefinedSerializer()),
103 |     FieldMetadata(
104 |         "bypassEncoding", "bypass_encoding", "_bypass_encoding", bool, None, PredefinedSerializer(), optional=True
105 |     ),
106 |     FieldMetadata("expiry", "expiry", "_expiry", timedelta, None, TimeDeltaSerializer()),
107 | ]
108 | 


--------------------------------------------------------------------------------
/kagglesdk/competitions/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/competitions/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/competitions/services/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/competitions/services/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/competitions/types/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/competitions/types/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/competitions/types/competition_enums.py:
--------------------------------------------------------------------------------
 1 | import enum
 2 | 
 3 | 
 4 | class CompetitionListTab(enum.Enum):
 5 |     COMPETITION_LIST_TAB_GENERAL = 0
 6 |     """TODO(aip.dev/126): (-- api-linter: core::0126::unspecified=disabled --)"""
 7 |     COMPETITION_LIST_TAB_ENTERED = 1
 8 |     COMPETITION_LIST_TAB_COMMUNITY = 2
 9 |     COMPETITION_LIST_TAB_HOSTED = 3
10 |     COMPETITION_LIST_TAB_UNLAUNCHED = 4
11 |     COMPETITION_LIST_TAB_UNLAUNCHED_COMMUNITY = 5
12 |     COMPETITION_LIST_TAB_EVERYTHING = 6
13 | 
14 | 
15 | class CompetitionSortBy(enum.Enum):
16 |     COMPETITION_SORT_BY_GROUPED = 0
17 |     """TODO(aip.dev/126): (-- api-linter: core::0126::unspecified=disabled --)"""
18 |     COMPETITION_SORT_BY_BEST = 1
19 |     COMPETITION_SORT_BY_PRIZE = 2
20 |     COMPETITION_SORT_BY_EARLIEST_DEADLINE = 3
21 |     COMPETITION_SORT_BY_LATEST_DEADLINE = 4
22 |     COMPETITION_SORT_BY_NUMBER_OF_TEAMS = 5
23 |     COMPETITION_SORT_BY_RELEVANCE = 6
24 |     COMPETITION_SORT_BY_RECENTLY_CREATED = 7
25 | 
26 | 
27 | class HostSegment(enum.Enum):
28 |     r"""
29 |     NOTE: Keep in Sync with Kaggle.Entities.HostSegment until migrated! Also keep
30 |     the comment in
31 |     competition_service.ListCompetitionsRequest.Selector.host_segment_id_filter
32 |     up to date
33 |     """
34 | 
35 |     HOST_SEGMENT_UNSPECIFIED = 0
36 |     HOST_SEGMENT_FEATURED = 1
37 |     HOST_SEGMENT_GETTING_STARTED = 5
38 |     HOST_SEGMENT_MASTERS = 6
39 |     HOST_SEGMENT_PLAYGROUND = 8
40 |     HOST_SEGMENT_RECRUITMENT = 3
41 |     HOST_SEGMENT_RESEARCH = 2
42 |     HOST_SEGMENT_COMMUNITY = 10
43 |     HOST_SEGMENT_ANALYTICS = 11
44 | 
45 | 
46 | class SubmissionGroup(enum.Enum):
47 |     SUBMISSION_GROUP_ALL = 0
48 |     """TODO(aip.dev/126): (-- api-linter: core::0126::unspecified=disabled --)"""
49 |     SUBMISSION_GROUP_SUCCESSFUL = 1
50 |     SUBMISSION_GROUP_SELECTED = 2
51 | 
52 | 
53 | class SubmissionSortBy(enum.Enum):
54 |     SUBMISSION_SORT_BY_DATE = 0
55 |     """TODO(aip.dev/126): (-- api-linter: core::0126::unspecified=disabled --)"""
56 |     SUBMISSION_SORT_BY_NAME = 1
57 |     SUBMISSION_SORT_BY_PRIVATE_SCORE = 2
58 |     SUBMISSION_SORT_BY_PUBLIC_SCORE = 3
59 | 


--------------------------------------------------------------------------------
/kagglesdk/competitions/types/submission_status.py:
--------------------------------------------------------------------------------
 1 | import enum
 2 | 
 3 | 
 4 | class SubmissionStatus(enum.Enum):
 5 |     """TODO(aip.dev/216): (-- api-linter: core::0216::synonyms=disabled --)"""
 6 | 
 7 |     PENDING = 0
 8 |     """TODO(aip.dev/126): (-- api-linter: core::0126::unspecified=disabled --)"""
 9 |     COMPLETE = 1
10 |     ERROR = 2
11 | 


--------------------------------------------------------------------------------
/kagglesdk/datasets/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/datasets/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/datasets/services/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/datasets/services/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/datasets/types/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/datasets/types/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/datasets/types/dataset_enums.py:
--------------------------------------------------------------------------------
 1 | import enum
 2 | 
 3 | 
 4 | class DatabundleVersionStatus(enum.Enum):
 5 |     NOT_YET_PERSISTED = 0
 6 |     BLOBS_RECEIVED = 1
 7 |     BLOBS_DECOMPRESSED = 2
 8 |     BLOBS_COPIED_TO_SDS = 3
 9 |     INDIVIDUAL_BLOBS_COMPRESSED = 4
10 |     READY = 5
11 |     FAILED = 6
12 |     DELETED = 7
13 |     REPROCESSING = 8
14 | 
15 | 
16 | class DatasetFileTypeGroup(enum.Enum):
17 |     r"""
18 |     This enum drives acceptable values from the python API, so avoid changing
19 |     enum member names if possible
20 |     """
21 | 
22 |     DATASET_FILE_TYPE_GROUP_ALL = 0
23 |     DATASET_FILE_TYPE_GROUP_CSV = 1
24 |     DATASET_FILE_TYPE_GROUP_SQLITE = 2
25 |     DATASET_FILE_TYPE_GROUP_JSON = 3
26 |     DATASET_FILE_TYPE_GROUP_BIG_QUERY = 4
27 | 
28 | 
29 | class DatasetLicenseGroup(enum.Enum):
30 |     r"""
31 |     This enum drives acceptable values from the python API, so avoid changing
32 |     enum member names if possible
33 |     """
34 | 
35 |     DATASET_LICENSE_GROUP_ALL = 0
36 |     DATASET_LICENSE_GROUP_CC = 1
37 |     DATASET_LICENSE_GROUP_GPL = 2
38 |     DATASET_LICENSE_GROUP_ODB = 3
39 |     DATASET_LICENSE_GROUP_OTHER = 4
40 | 
41 | 
42 | class DatasetSelectionGroup(enum.Enum):
43 |     DATASET_SELECTION_GROUP_PUBLIC = 0
44 |     DATASET_SELECTION_GROUP_MY = 1
45 |     DATASET_SELECTION_GROUP_USER = 2
46 |     DATASET_SELECTION_GROUP_USER_SHARED_WITH_ME = 3
47 |     DATASET_SELECTION_GROUP_UPVOTED = 4
48 |     DATASET_SELECTION_GROUP_MY_PRIVATE = 5
49 |     DATASET_SELECTION_GROUP_MY_PUBLIC = 10
50 |     DATASET_SELECTION_GROUP_ORGANIZATION = 6
51 |     DATASET_SELECTION_GROUP_BOOKMARKED = 11
52 |     DATASET_SELECTION_GROUP_COLLABORATION = 12
53 |     DATASET_SELECTION_GROUP_SHARED_WITH_USER = 13
54 |     DATASET_SELECTION_GROUP_FEATURED = 7
55 |     """Old"""
56 |     DATASET_SELECTION_GROUP_ALL = 8
57 |     DATASET_SELECTION_GROUP_UNFEATURED = 9
58 | 
59 | 
60 | class DatasetSizeGroup(enum.Enum):
61 |     r"""
62 |     This enum drives acceptable values from the python API, so avoid changing
63 |     enum member names if possible
64 |     """
65 | 
66 |     DATASET_SIZE_GROUP_ALL = 0
67 |     DATASET_SIZE_GROUP_SMALL = 1
68 |     DATASET_SIZE_GROUP_MEDIUM = 2
69 |     DATASET_SIZE_GROUP_LARGE = 3
70 | 
71 | 
72 | class DatasetSortBy(enum.Enum):
73 |     r"""
74 |     This enum drives acceptable values from the python API, so avoid changing
75 |     enum member names if possible
76 |     """
77 | 
78 |     DATASET_SORT_BY_HOTTEST = 0
79 |     DATASET_SORT_BY_VOTES = 1
80 |     DATASET_SORT_BY_UPDATED = 2
81 |     DATASET_SORT_BY_ACTIVE = 3
82 |     """Deprecated"""
83 |     DATASET_SORT_BY_PUBLISHED = 4
84 |     DATASET_SORT_BY_RELEVANCE = 5
85 |     """Old world"""
86 |     DATASET_SORT_BY_LAST_VIEWED = 6
87 |     DATASET_SORT_BY_USABILITY = 7
88 | 
89 | 
90 | class DatasetViewedGroup(enum.Enum):
91 |     DATASET_VIEWED_GROUP_UNSPECIFIED = 0
92 |     DATASET_VIEWED_GROUP_VIEWED = 1
93 | 


--------------------------------------------------------------------------------
/kagglesdk/education/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/education/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/education/services/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/education/services/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/education/services/education_api_service.py:
--------------------------------------------------------------------------------
 1 | from kagglesdk.education.types.education_api_service import (
 2 |     ApiTrackExerciseInteractionRequest,
 3 |     ApiTrackExerciseInteractionResponse,
 4 | )
 5 | from kagglesdk.kaggle_http_client import KaggleHttpClient
 6 | 
 7 | 
 8 | class EducationApiClient(object):
 9 | 
10 |     def __init__(self, client: KaggleHttpClient):
11 |         self._client = client
12 | 
13 |     def track_exercise_interaction(
14 |         self, request: ApiTrackExerciseInteractionRequest = None
15 |     ) -> ApiTrackExerciseInteractionResponse:
16 |         r"""
17 |         Args:
18 |           request (ApiTrackExerciseInteractionRequest):
19 |             The request object; initialized to empty instance if not specified.
20 |         """
21 | 
22 |         if request is None:
23 |             request = ApiTrackExerciseInteractionRequest()
24 | 
25 |         return self._client.call(
26 |             "education.EducationApiService", "ApiTrackExerciseInteraction", request, ApiTrackExerciseInteractionResponse
27 |         )
28 | 


--------------------------------------------------------------------------------
/kagglesdk/education/types/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/education/types/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/education/types/education_service.py:
--------------------------------------------------------------------------------
  1 | import enum
  2 | from kagglesdk.kaggle_object import *
  3 | from typing import Optional
  4 | 
  5 | 
  6 | class LearnExerciseInteractionType(enum.Enum):
  7 |     LEARN_EXERCISE_INTERACTION_TYPE_UNSPECIFIED = 0
  8 |     CHECK = 1
  9 |     HINT = 2
 10 |     SOLUTION = 3
 11 | 
 12 | 
 13 | class LearnExerciseOutcomeType(enum.Enum):
 14 |     LEARN_EXERCISE_OUTCOME_TYPE_UNSPECIFIED = 0
 15 |     PASS = 1
 16 |     FAIL = 2
 17 |     EXCEPTION = 3
 18 |     UNATTEMPTED = 4
 19 | 
 20 | 
 21 | class LearnExerciseQuestionType(enum.Enum):
 22 |     LEARN_EXERCISE_QUESTION_TYPE_UNSPECIFIED = 0
 23 |     EQUALITY_CHECK_PROBLEM = 1
 24 |     CODING_PROBLEM = 2
 25 |     FUNCTION_PROBLEM = 3
 26 |     THOUGHT_EXPERIMENT = 4
 27 | 
 28 | 
 29 | class LearnNudgeType(enum.Enum):
 30 |     COURSE_COMPLETE_NO_BONUS_LESSONS = 0
 31 |     COURSE_COMPLETE_WITH_BONUS_LESSONS = 1
 32 |     COURSE_INCOMPLETE = 2
 33 |     DO_EXERCISE = 3
 34 |     DO_TUTORIAL = 4
 35 | 
 36 | 
 37 | class LearnNudge(KaggleObject):
 38 |     r"""
 39 |     Attributes:
 40 |       course_index (int)
 41 |       course_name (str)
 42 |       course_slug (str)
 43 |       next_item_name (str)
 44 |       next_item_url (str)
 45 |       next_item_type (LearnNudgeType)
 46 |     """
 47 | 
 48 |     def __init__(self):
 49 |         self._course_index = 0
 50 |         self._course_name = ""
 51 |         self._course_slug = ""
 52 |         self._next_item_name = ""
 53 |         self._next_item_url = ""
 54 |         self._next_item_type = LearnNudgeType.COURSE_COMPLETE_NO_BONUS_LESSONS
 55 |         self._freeze()
 56 | 
 57 |     @property
 58 |     def course_index(self) -> int:
 59 |         return self._course_index
 60 | 
 61 |     @course_index.setter
 62 |     def course_index(self, course_index: int):
 63 |         if course_index is None:
 64 |             del self.course_index
 65 |             return
 66 |         if not isinstance(course_index, int):
 67 |             raise TypeError('course_index must be of type int')
 68 |         self._course_index = course_index
 69 | 
 70 |     @property
 71 |     def course_name(self) -> str:
 72 |         return self._course_name
 73 | 
 74 |     @course_name.setter
 75 |     def course_name(self, course_name: str):
 76 |         if course_name is None:
 77 |             del self.course_name
 78 |             return
 79 |         if not isinstance(course_name, str):
 80 |             raise TypeError('course_name must be of type str')
 81 |         self._course_name = course_name
 82 | 
 83 |     @property
 84 |     def course_slug(self) -> str:
 85 |         return self._course_slug
 86 | 
 87 |     @course_slug.setter
 88 |     def course_slug(self, course_slug: str):
 89 |         if course_slug is None:
 90 |             del self.course_slug
 91 |             return
 92 |         if not isinstance(course_slug, str):
 93 |             raise TypeError('course_slug must be of type str')
 94 |         self._course_slug = course_slug
 95 | 
 96 |     @property
 97 |     def next_item_name(self) -> str:
 98 |         return self._next_item_name
 99 | 
100 |     @next_item_name.setter
101 |     def next_item_name(self, next_item_name: str):
102 |         if next_item_name is None:
103 |             del self.next_item_name
104 |             return
105 |         if not isinstance(next_item_name, str):
106 |             raise TypeError('next_item_name must be of type str')
107 |         self._next_item_name = next_item_name
108 | 
109 |     @property
110 |     def next_item_url(self) -> str:
111 |         return self._next_item_url
112 | 
113 |     @next_item_url.setter
114 |     def next_item_url(self, next_item_url: str):
115 |         if next_item_url is None:
116 |             del self.next_item_url
117 |             return
118 |         if not isinstance(next_item_url, str):
119 |             raise TypeError('next_item_url must be of type str')
120 |         self._next_item_url = next_item_url
121 | 
122 |     @property
123 |     def next_item_type(self) -> 'LearnNudgeType':
124 |         return self._next_item_type
125 | 
126 |     @next_item_type.setter
127 |     def next_item_type(self, next_item_type: 'LearnNudgeType'):
128 |         if next_item_type is None:
129 |             del self.next_item_type
130 |             return
131 |         if not isinstance(next_item_type, LearnNudgeType):
132 |             raise TypeError('next_item_type must be of type LearnNudgeType')
133 |         self._next_item_type = next_item_type
134 | 
135 | 
136 | LearnNudge._fields = [
137 |     FieldMetadata("courseIndex", "course_index", "_course_index", int, 0, PredefinedSerializer()),
138 |     FieldMetadata("courseName", "course_name", "_course_name", str, "", PredefinedSerializer()),
139 |     FieldMetadata("courseSlug", "course_slug", "_course_slug", str, "", PredefinedSerializer()),
140 |     FieldMetadata("nextItemName", "next_item_name", "_next_item_name", str, "", PredefinedSerializer()),
141 |     FieldMetadata("nextItemUrl", "next_item_url", "_next_item_url", str, "", PredefinedSerializer()),
142 |     FieldMetadata(
143 |         "nextItemType",
144 |         "next_item_type",
145 |         "_next_item_type",
146 |         LearnNudgeType,
147 |         LearnNudgeType.COURSE_COMPLETE_NO_BONUS_LESSONS,
148 |         EnumSerializer(),
149 |     ),
150 | ]
151 | 


--------------------------------------------------------------------------------
/kagglesdk/kaggle_client.py:
--------------------------------------------------------------------------------
 1 | from kagglesdk.kernels.services.kernels_api_service import KernelsApiClient
 2 | from kagglesdk.blobs.services.blob_api_service import BlobApiClient
 3 | from kagglesdk.education.services.education_api_service import EducationApiClient
 4 | from kagglesdk.models.services.model_api_service import ModelApiClient
 5 | from kagglesdk.models.services.model_service import ModelClient
 6 | from kagglesdk.competitions.services.competition_api_service import CompetitionApiClient
 7 | from kagglesdk.datasets.services.dataset_api_service import DatasetApiClient
 8 | from kagglesdk.admin.services.inbox_file_service import InboxFileClient
 9 | from kagglesdk.security.services.oauth_service import OAuthClient
10 | from kagglesdk.users.services.account_service import AccountClient
11 | from kagglesdk.kaggle_env import KaggleEnv
12 | from kagglesdk.kaggle_http_client import KaggleHttpClient
13 | 
14 | 
15 | class KaggleClient(object):
16 |     class Kernels(object):
17 |         def __init__(self, http_client: KaggleHttpClient):
18 |             self.kernels_api_client = KernelsApiClient(http_client)
19 | 
20 |     class Blobs(object):
21 |         def __init__(self, http_client: KaggleHttpClient):
22 |             self.blob_api_client = BlobApiClient(http_client)
23 | 
24 |     class Education(object):
25 |         def __init__(self, http_client: KaggleHttpClient):
26 |             self.education_api_client = EducationApiClient(http_client)
27 | 
28 |     class Models(object):
29 |         def __init__(self, http_client: KaggleHttpClient):
30 |             self.model_api_client = ModelApiClient(http_client)
31 |             self.model_client = ModelClient(http_client)
32 | 
33 |     class Competitions(object):
34 |         def __init__(self, http_client: KaggleHttpClient):
35 |             self.competition_api_client = CompetitionApiClient(http_client)
36 | 
37 |     class Datasets(object):
38 |         def __init__(self, http_client: KaggleHttpClient):
39 |             self.dataset_api_client = DatasetApiClient(http_client)
40 | 
41 |     class Admin(object):
42 |         def __init__(self, http_client: KaggleHttpClient):
43 |             self.inbox_file_client = InboxFileClient(http_client)
44 | 
45 |     class Security(object):
46 |         def __init__(self, http_client: KaggleHttpClient):
47 |             self.oauth_client = OAuthClient(http_client)
48 | 
49 |     class Users(object):
50 |         def __init__(self, http_client: KaggleHttpClient):
51 |             self.account_client = AccountClient(http_client)
52 | 
53 |     def __init__(self, env: KaggleEnv = None, verbose: bool = False, username: str = None, password: str = None):
54 |         self._http_client = http_client = KaggleHttpClient(
55 |             env, verbose, self._renew_iap_token, username=username, password=password
56 |         )
57 |         self.kernels = KaggleClient.Kernels(http_client)
58 |         self.blobs = KaggleClient.Blobs(http_client)
59 |         self.education = KaggleClient.Education(http_client)
60 |         self.models = KaggleClient.Models(http_client)
61 |         self.competitions = KaggleClient.Competitions(http_client)
62 |         self.datasets = KaggleClient.Datasets(http_client)
63 |         self.admin = KaggleClient.Admin(http_client)
64 |         self.security = KaggleClient.Security(http_client)
65 |         self.users = KaggleClient.Users(http_client)
66 |         self.username = username
67 |         self.password = password
68 | 
69 |     def http_client(self):
70 |         return self._http_client
71 | 
72 |     def _renew_iap_token(self):
73 |         return self.admin.admin_client.renew_iap_token()
74 | 
75 |     def __enter__(self):
76 |         self._http_client.__enter__()
77 |         return self
78 | 
79 |     def __exit__(self, exc_type, exc_value, tb):
80 |         self._http_client.__exit__(exc_type, exc_value, tb)
81 | 


--------------------------------------------------------------------------------
/kagglesdk/kaggle_env.py:
--------------------------------------------------------------------------------
 1 | import os
 2 | from enum import Enum
 3 | 
 4 | 
 5 | class KaggleEnv(Enum):
 6 |     LOCAL = 0  # localhost
 7 |     STAGING = 1  # staging.kaggle.com
 8 |     ADMIN = 2  # admin.kaggle.com
 9 |     QA = 3  # qa.kaggle.com
10 |     # Direct prod access is not allowed to have IAP protection during testing, but we support basic auth.
11 |     PROD = 4  # www.kaggle.com
12 | 
13 | 
14 | _env_to_endpoint = {
15 |     KaggleEnv.LOCAL: 'http://localhost',
16 |     KaggleEnv.STAGING: 'https://staging.kaggle.com',
17 |     KaggleEnv.ADMIN: 'https://admin.kaggle.com',
18 |     KaggleEnv.QA: 'https://qa.kaggle.com',
19 |     # See the comment above in KaggleEnv enum.
20 |     KaggleEnv.PROD: 'https://www.kaggle.com',
21 | }
22 | 
23 | 
24 | def get_endpoint(env: KaggleEnv):
25 |     return _env_to_endpoint[env]
26 | 
27 | 
28 | def get_env():
29 |     env = os.getenv('KAGGLE_API_ENVIRONMENT')
30 |     if env is None or env == 'PROD':
31 |         return KaggleEnv.PROD
32 |     if env == 'LOCALHOST':
33 |         return KaggleEnv.LOCAL
34 |     if env == 'ADMIN':
35 |         return KaggleEnv.ADMIN
36 |     if env == 'STAGING':
37 |         return KaggleEnv.STAGING
38 |     if env == 'QA':
39 |         return KaggleEnv.QA
40 |     raise Exception(f'Unrecognized value in KAGGLE_API_ENVIRONMENT: "{env}"')
41 | 


--------------------------------------------------------------------------------
/kagglesdk/kernels/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/kernels/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/kernels/services/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/kernels/services/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/kernels/services/kernels_api_service.py:
--------------------------------------------------------------------------------
  1 | from kagglesdk.common.types.file_download import FileDownload
  2 | from kagglesdk.common.types.http_redirect import HttpRedirect
  3 | from kagglesdk.kaggle_http_client import KaggleHttpClient
  4 | from kagglesdk.kernels.types.kernels_api_service import (
  5 |     ApiDownloadKernelOutputRequest,
  6 |     ApiDownloadKernelOutputZipRequest,
  7 |     ApiGetKernelRequest,
  8 |     ApiGetKernelResponse,
  9 |     ApiGetKernelSessionStatusRequest,
 10 |     ApiGetKernelSessionStatusResponse,
 11 |     ApiListKernelFilesRequest,
 12 |     ApiListKernelFilesResponse,
 13 |     ApiListKernelSessionOutputRequest,
 14 |     ApiListKernelSessionOutputResponse,
 15 |     ApiListKernelsRequest,
 16 |     ApiListKernelsResponse,
 17 |     ApiSaveKernelRequest,
 18 |     ApiSaveKernelResponse,
 19 | )
 20 | 
 21 | 
 22 | class KernelsApiClient(object):
 23 | 
 24 |     def __init__(self, client: KaggleHttpClient):
 25 |         self._client = client
 26 | 
 27 |     def list_kernels(self, request: ApiListKernelsRequest = None) -> ApiListKernelsResponse:
 28 |         r"""
 29 |         Args:
 30 |           request (ApiListKernelsRequest):
 31 |             The request object; initialized to empty instance if not specified.
 32 |         """
 33 | 
 34 |         if request is None:
 35 |             request = ApiListKernelsRequest()
 36 | 
 37 |         return self._client.call("kernels.KernelsApiService", "ApiListKernels", request, ApiListKernelsResponse)
 38 | 
 39 |     def list_kernel_files(self, request: ApiListKernelFilesRequest = None) -> ApiListKernelFilesResponse:
 40 |         r"""
 41 |         Args:
 42 |           request (ApiListKernelFilesRequest):
 43 |             The request object; initialized to empty instance if not specified.
 44 |         """
 45 | 
 46 |         if request is None:
 47 |             request = ApiListKernelFilesRequest()
 48 | 
 49 |         return self._client.call("kernels.KernelsApiService", "ApiListKernelFiles", request, ApiListKernelFilesResponse)
 50 | 
 51 |     def get_kernel(self, request: ApiGetKernelRequest = None) -> ApiGetKernelResponse:
 52 |         r"""
 53 |         Args:
 54 |           request (ApiGetKernelRequest):
 55 |             The request object; initialized to empty instance if not specified.
 56 |         """
 57 | 
 58 |         if request is None:
 59 |             request = ApiGetKernelRequest()
 60 | 
 61 |         return self._client.call("kernels.KernelsApiService", "ApiGetKernel", request, ApiGetKernelResponse)
 62 | 
 63 |     def save_kernel(self, request: ApiSaveKernelRequest = None) -> ApiSaveKernelResponse:
 64 |         r"""
 65 |         Args:
 66 |           request (ApiSaveKernelRequest):
 67 |             The request object; initialized to empty instance if not specified.
 68 |         """
 69 | 
 70 |         if request is None:
 71 |             request = ApiSaveKernelRequest()
 72 | 
 73 |         return self._client.call("kernels.KernelsApiService", "ApiSaveKernel", request, ApiSaveKernelResponse)
 74 | 
 75 |     def list_kernel_session_output(
 76 |         self, request: ApiListKernelSessionOutputRequest = None
 77 |     ) -> ApiListKernelSessionOutputResponse:
 78 |         r"""
 79 |         Args:
 80 |           request (ApiListKernelSessionOutputRequest):
 81 |             The request object; initialized to empty instance if not specified.
 82 |         """
 83 | 
 84 |         if request is None:
 85 |             request = ApiListKernelSessionOutputRequest()
 86 | 
 87 |         return self._client.call(
 88 |             "kernels.KernelsApiService", "ApiListKernelSessionOutput", request, ApiListKernelSessionOutputResponse
 89 |         )
 90 | 
 91 |     def get_kernel_session_status(
 92 |         self, request: ApiGetKernelSessionStatusRequest = None
 93 |     ) -> ApiGetKernelSessionStatusResponse:
 94 |         r"""
 95 |         Args:
 96 |           request (ApiGetKernelSessionStatusRequest):
 97 |             The request object; initialized to empty instance if not specified.
 98 |         """
 99 | 
100 |         if request is None:
101 |             request = ApiGetKernelSessionStatusRequest()
102 | 
103 |         return self._client.call(
104 |             "kernels.KernelsApiService", "ApiGetKernelSessionStatus", request, ApiGetKernelSessionStatusResponse
105 |         )
106 | 
107 |     def download_kernel_output(self, request: ApiDownloadKernelOutputRequest = None) -> HttpRedirect:
108 |         r"""
109 |         Meant for use by Kaggle Hub (http bindings and terminology align with that)
110 | 
111 |         Args:
112 |           request (ApiDownloadKernelOutputRequest):
113 |             The request object; initialized to empty instance if not specified.
114 |         """
115 | 
116 |         if request is None:
117 |             request = ApiDownloadKernelOutputRequest()
118 | 
119 |         return self._client.call("kernels.KernelsApiService", "ApiDownloadKernelOutput", request, HttpRedirect)
120 | 
121 |     def download_kernel_output_zip(self, request: ApiDownloadKernelOutputZipRequest = None) -> FileDownload:
122 |         r"""
123 |         Meant for use by Kaggle Hub (and DownloadKernelOutput above)
124 | 
125 |         Args:
126 |           request (ApiDownloadKernelOutputZipRequest):
127 |             The request object; initialized to empty instance if not specified.
128 |         """
129 | 
130 |         if request is None:
131 |             request = ApiDownloadKernelOutputZipRequest()
132 | 
133 |         return self._client.call("kernels.KernelsApiService", "ApiDownloadKernelOutputZip", request, FileDownload)
134 | 


--------------------------------------------------------------------------------
/kagglesdk/kernels/types/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/kernels/types/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/kernels/types/kernels_enums.py:
--------------------------------------------------------------------------------
 1 | import enum
 2 | 
 3 | 
 4 | class KernelsListSortType(enum.Enum):
 5 |     HOTNESS = 0
 6 |     COMMENT_COUNT = 1
 7 |     DATE_CREATED = 2
 8 |     DATE_RUN = 3
 9 |     RELEVANCE = 4
10 |     SCORE_ASCENDING = 5
11 |     SCORE_DESCENDING = 6
12 |     VIEW_COUNT = 7
13 |     VOTE_COUNT = 8
14 | 
15 | 
16 | class KernelsListViewType(enum.Enum):
17 |     KERNELS_LIST_VIEW_TYPE_UNSPECIFIED = 0
18 |     PROFILE = 1
19 |     UPVOTED = 2
20 |     EVERYONE = 3
21 |     COLLABORATION = 4
22 |     FORK = 5
23 |     BOOKMARKED = 6
24 |     RECENTLY_VIEWED = 7
25 |     PUBLIC_AND_USERS_PRIVATE = 8
26 | 
27 | 
28 | class KernelWorkerStatus(enum.Enum):
29 |     QUEUED = 0
30 |     RUNNING = 1
31 |     COMPLETE = 2
32 |     ERROR = 3
33 |     CANCEL_REQUESTED = 4
34 |     CANCEL_ACKNOWLEDGED = 5
35 |     NEW_SCRIPT = 6
36 | 


--------------------------------------------------------------------------------
/kagglesdk/models/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/models/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/models/services/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/models/services/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/models/services/model_service.py:
--------------------------------------------------------------------------------
 1 | from kagglesdk.kaggle_http_client import KaggleHttpClient
 2 | from kagglesdk.models.types.model_service import GetModelMetricsRequest, GetModelMetricsResponse
 3 | 
 4 | 
 5 | class ModelClient(object):
 6 | 
 7 |     def __init__(self, client: KaggleHttpClient):
 8 |         self._client = client
 9 | 
10 |     def get_model_metrics(self, request: GetModelMetricsRequest = None) -> GetModelMetricsResponse:
11 |         r"""
12 |         Args:
13 |           request (GetModelMetricsRequest):
14 |             The request object; initialized to empty instance if not specified.
15 |         """
16 | 
17 |         if request is None:
18 |             request = GetModelMetricsRequest()
19 | 
20 |         return self._client.call("models.ModelService", "GetModelMetrics", request, GetModelMetricsResponse)
21 | 


--------------------------------------------------------------------------------
/kagglesdk/models/types/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/models/types/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/models/types/model_enums.py:
--------------------------------------------------------------------------------
 1 | import enum
 2 | 
 3 | 
 4 | class GatingAgreementRequestsReviewStatus(enum.Enum):
 5 |     GATING_AGREEMENT_REQUESTS_REVIEW_STATUS_UNSPECIFIED = 0
 6 |     GATING_AGREEMENT_REQUESTS_REVIEW_STATUS_PENDING = 1
 7 |     GATING_AGREEMENT_REQUESTS_REVIEW_STATUS_ACCEPTED = 2
 8 |     GATING_AGREEMENT_REQUESTS_REVIEW_STATUS_REJECTED = 3
 9 | 
10 | 
11 | class ListModelsOrderBy(enum.Enum):
12 |     LIST_MODELS_ORDER_BY_UNSPECIFIED = 0
13 |     LIST_MODELS_ORDER_BY_HOTNESS = 1
14 |     LIST_MODELS_ORDER_BY_DOWNLOAD_COUNT = 2
15 |     LIST_MODELS_ORDER_BY_VOTE_COUNT = 3
16 |     LIST_MODELS_ORDER_BY_NOTEBOOK_COUNT = 4
17 |     LIST_MODELS_ORDER_BY_PUBLISH_TIME = 5
18 |     LIST_MODELS_ORDER_BY_CREATE_TIME = 6
19 |     LIST_MODELS_ORDER_BY_UPDATE_TIME = 7
20 |     LIST_MODELS_ORDER_BY_VIEW_TIME_DESC = 8
21 | 
22 | 
23 | class ModelFramework(enum.Enum):
24 |     MODEL_FRAMEWORK_UNSPECIFIED = 0
25 |     MODEL_FRAMEWORK_TENSOR_FLOW_1 = 1
26 |     MODEL_FRAMEWORK_TENSOR_FLOW_2 = 2
27 |     MODEL_FRAMEWORK_TF_LITE = 3
28 |     MODEL_FRAMEWORK_TF_JS = 4
29 |     MODEL_FRAMEWORK_PY_TORCH = 5
30 |     MODEL_FRAMEWORK_JAX = 6
31 |     MODEL_FRAMEWORK_FLAX = 14
32 |     MODEL_FRAMEWORK_PAX = 15
33 |     MODEL_FRAMEWORK_MAX_TEXT = 17
34 |     MODEL_FRAMEWORK_GEMMA_CPP = 18
35 |     MODEL_FRAMEWORK_GGML = 19
36 |     MODEL_FRAMEWORK_GGUF = 21
37 |     MODEL_FRAMEWORK_CORAL = 7
38 |     MODEL_FRAMEWORK_SCIKIT_LEARN = 8
39 |     MODEL_FRAMEWORK_MXNET = 9
40 |     MODEL_FRAMEWORK_ONNX = 10
41 |     MODEL_FRAMEWORK_KERAS = 11
42 |     MODEL_FRAMEWORK_TRANSFORMERS = 16
43 |     MODEL_FRAMEWORK_API = 12
44 |     MODEL_FRAMEWORK_OTHER = 13
45 |     MODEL_FRAMEWORK_TENSOR_RT_LLM = 20
46 |     MODEL_FRAMEWORK_TRITON = 22
47 | 
48 | 
49 | class ModelInstanceType(enum.Enum):
50 |     MODEL_INSTANCE_TYPE_UNSPECIFIED = 0
51 |     MODEL_INSTANCE_TYPE_BASE_MODEL = 1
52 |     MODEL_INSTANCE_TYPE_KAGGLE_VARIANT = 2
53 |     MODEL_INSTANCE_TYPE_EXTERNAL_VARIANT = 3
54 | 
55 | 
56 | class ModelVersionLinkType(enum.Enum):
57 |     MODEL_VERSION_LINK_TYPE_UNSPECIFIED = 0
58 |     MODEL_VERSION_LINK_TYPE_VERTEX_OPEN = 1
59 |     MODEL_VERSION_LINK_TYPE_VERTEX_DEPLOY = 2
60 | 
61 | 
62 | class GatingAgreementRequestsExpiryStatus(enum.Enum):
63 |     GATING_AGREEMENT_REQUESTS_EXPIRY_STATUS_UNSPECIFIED = 0
64 |     GATING_AGREEMENT_REQUESTS_EXPIRY_STATUS_NOT_EXPIRED = 1
65 |     GATING_AGREEMENT_REQUESTS_EXPIRY_STATUS_IS_EXPIRED = 2
66 | 


--------------------------------------------------------------------------------
/kagglesdk/security/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/security/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/security/services/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/security/services/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/security/services/oauth_service.py:
--------------------------------------------------------------------------------
 1 | from kagglesdk.common.types.http_redirect import HttpRedirect
 2 | from kagglesdk.kaggle_http_client import KaggleHttpClient
 3 | from kagglesdk.security.types.oauth_service import (
 4 |     ExchangeOAuthTokenRequest,
 5 |     ExchangeOAuthTokenResponse,
 6 |     StartOAuthFlowRequest,
 7 | )
 8 | 
 9 | 
10 | class OAuthClient(object):
11 | 
12 |     def __init__(self, client: KaggleHttpClient):
13 |         self._client = client
14 | 
15 |     def start_oauth_flow(self, request: StartOAuthFlowRequest = None) -> HttpRedirect:
16 |         r"""
17 |         Args:
18 |           request (StartOAuthFlowRequest):
19 |             The request object; initialized to empty instance if not specified.
20 |         """
21 | 
22 |         if request is None:
23 |             request = StartOAuthFlowRequest()
24 | 
25 |         return self._client.call("security.OAuthService", "StartOAuthFlow", request, HttpRedirect)
26 | 
27 |     def exchange_oauth_token(self, request: ExchangeOAuthTokenRequest = None) -> ExchangeOAuthTokenResponse:
28 |         r"""
29 |         Args:
30 |           request (ExchangeOAuthTokenRequest):
31 |             The request object; initialized to empty instance if not specified.
32 |         """
33 | 
34 |         if request is None:
35 |             request = ExchangeOAuthTokenRequest()
36 | 
37 |         return self._client.call("security.OAuthService", "ExchangeOAuthToken", request, ExchangeOAuthTokenResponse)
38 | 


--------------------------------------------------------------------------------
/kagglesdk/security/types/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/security/types/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/security/types/authentication.py:
--------------------------------------------------------------------------------
  1 | from kagglesdk.kaggle_object import *
  2 | from typing import Optional, List
  3 | 
  4 | 
  5 | class AuthorizationScope(KaggleObject):
  6 |     r"""
  7 |     Attributes:
  8 |       resource_id (int)
  9 |       permission (AuthorizationPermissionScope)
 10 |       role (AuthorizationRoleScope)
 11 |     """
 12 | 
 13 |     def __init__(self):
 14 |         self._resource_id = 0
 15 |         self._permission = None
 16 |         self._role = None
 17 |         self._freeze()
 18 | 
 19 |     @property
 20 |     def resource_id(self) -> int:
 21 |         return self._resource_id
 22 | 
 23 |     @resource_id.setter
 24 |     def resource_id(self, resource_id: int):
 25 |         if resource_id is None:
 26 |             del self.resource_id
 27 |             return
 28 |         if not isinstance(resource_id, int):
 29 |             raise TypeError('resource_id must be of type int')
 30 |         self._resource_id = resource_id
 31 | 
 32 |     @property
 33 |     def permission(self) -> Optional['AuthorizationPermissionScope']:
 34 |         return self._permission or None
 35 | 
 36 |     @permission.setter
 37 |     def permission(self, permission: Optional['AuthorizationPermissionScope']):
 38 |         if permission is None:
 39 |             del self.permission
 40 |             return
 41 |         if not isinstance(permission, AuthorizationPermissionScope):
 42 |             raise TypeError('permission must be of type AuthorizationPermissionScope')
 43 |         del self.role
 44 |         self._permission = permission
 45 | 
 46 |     @property
 47 |     def role(self) -> Optional['AuthorizationRoleScope']:
 48 |         return self._role or None
 49 | 
 50 |     @role.setter
 51 |     def role(self, role: Optional['AuthorizationRoleScope']):
 52 |         if role is None:
 53 |             del self.role
 54 |             return
 55 |         if not isinstance(role, AuthorizationRoleScope):
 56 |             raise TypeError('role must be of type AuthorizationRoleScope')
 57 |         del self.permission
 58 |         self._role = role
 59 | 
 60 | 
 61 | class AuthorizationPermissionScope(KaggleObject):
 62 |     r"""
 63 |     Attributes:
 64 |       name (str)
 65 |       description (str)
 66 |     """
 67 | 
 68 |     def __init__(self):
 69 |         self._name = ""
 70 |         self._description = None
 71 |         self._freeze()
 72 | 
 73 |     @property
 74 |     def name(self) -> str:
 75 |         return self._name
 76 | 
 77 |     @name.setter
 78 |     def name(self, name: str):
 79 |         if name is None:
 80 |             del self.name
 81 |             return
 82 |         if not isinstance(name, str):
 83 |             raise TypeError('name must be of type str')
 84 |         self._name = name
 85 | 
 86 |     @property
 87 |     def description(self) -> str:
 88 |         return self._description or ""
 89 | 
 90 |     @description.setter
 91 |     def description(self, description: str):
 92 |         if description is None:
 93 |             del self.description
 94 |             return
 95 |         if not isinstance(description, str):
 96 |             raise TypeError('description must be of type str')
 97 |         self._description = description
 98 | 
 99 | 
100 | class AuthorizationRoleScope(KaggleObject):
101 |     r"""
102 |     Attributes:
103 |       name (str)
104 |       description (str)
105 |       permissions (AuthorizationPermissionScope)
106 |     """
107 | 
108 |     def __init__(self):
109 |         self._name = ""
110 |         self._description = None
111 |         self._permissions = []
112 |         self._freeze()
113 | 
114 |     @property
115 |     def name(self) -> str:
116 |         return self._name
117 | 
118 |     @name.setter
119 |     def name(self, name: str):
120 |         if name is None:
121 |             del self.name
122 |             return
123 |         if not isinstance(name, str):
124 |             raise TypeError('name must be of type str')
125 |         self._name = name
126 | 
127 |     @property
128 |     def description(self) -> str:
129 |         return self._description or ""
130 | 
131 |     @description.setter
132 |     def description(self, description: str):
133 |         if description is None:
134 |             del self.description
135 |             return
136 |         if not isinstance(description, str):
137 |             raise TypeError('description must be of type str')
138 |         self._description = description
139 | 
140 |     @property
141 |     def permissions(self) -> Optional[List[Optional['AuthorizationPermissionScope']]]:
142 |         return self._permissions
143 | 
144 |     @permissions.setter
145 |     def permissions(self, permissions: Optional[List[Optional['AuthorizationPermissionScope']]]):
146 |         if permissions is None:
147 |             del self.permissions
148 |             return
149 |         if not isinstance(permissions, list):
150 |             raise TypeError('permissions must be of type list')
151 |         if not all([isinstance(t, AuthorizationPermissionScope) for t in permissions]):
152 |             raise TypeError('permissions must contain only items of type AuthorizationPermissionScope')
153 |         self._permissions = permissions
154 | 
155 | 
156 | AuthorizationScope._fields = [
157 |     FieldMetadata("resourceId", "resource_id", "_resource_id", int, 0, PredefinedSerializer()),
158 |     FieldMetadata(
159 |         "permission",
160 |         "permission",
161 |         "_permission",
162 |         AuthorizationPermissionScope,
163 |         None,
164 |         KaggleObjectSerializer(),
165 |         optional=True,
166 |     ),
167 |     FieldMetadata("role", "role", "_role", AuthorizationRoleScope, None, KaggleObjectSerializer(), optional=True),
168 | ]
169 | 
170 | AuthorizationPermissionScope._fields = [
171 |     FieldMetadata("name", "name", "_name", str, "", PredefinedSerializer()),
172 |     FieldMetadata("description", "description", "_description", str, None, PredefinedSerializer(), optional=True),
173 | ]
174 | 
175 | AuthorizationRoleScope._fields = [
176 |     FieldMetadata("name", "name", "_name", str, "", PredefinedSerializer()),
177 |     FieldMetadata("description", "description", "_description", str, None, PredefinedSerializer(), optional=True),
178 |     FieldMetadata(
179 |         "permissions",
180 |         "permissions",
181 |         "_permissions",
182 |         AuthorizationPermissionScope,
183 |         [],
184 |         ListSerializer(KaggleObjectSerializer()),
185 |     ),
186 | ]
187 | 


--------------------------------------------------------------------------------
/kagglesdk/test/test_client.py:
--------------------------------------------------------------------------------
 1 | from kagglesdk import kaggle_env
 2 | from kagglesdk import KaggleClient, KaggleEnv
 3 | 
 4 | # python -m unittest tests.test_authenticate
 5 | 
 6 | import os
 7 | import unittest
 8 | 
 9 | 
10 | class TestClient(unittest.TestCase):
11 | 
12 |     def setUp(self):
13 |         print('setup             class:%s' % self)
14 | 
15 |     def tearDown(self):
16 |         print('teardown          class:TestStuff')
17 | 
18 |     # Environment
19 | 
20 |     def test_kaggle_environment(self):
21 |         os.environ['KAGGLE_API_ENVIRONMENT'] = 'PROD'
22 | 
23 |         env = kaggle_env.get_env()
24 |         self.assertEqual(env, KaggleEnv.PROD)
25 | 
26 |         endpoint = kaggle_env.get_endpoint(env)
27 |         self.assertEqual(endpoint, 'https://www.kaggle.com')
28 | 
29 |     # Client
30 | 
31 |     def test_kaggle_client(self):
32 |         client = KaggleClient(env=KaggleEnv.PROD, verbose=False, username='dinosaur', password='xxxxxxxxxxxx')
33 | 
34 |         self.assertEqual(client.username, 'dinosaur')
35 |         self.assertEqual(client.password, 'xxxxxxxxxxxx')
36 |         self.assertEqual(client.http_client()._endpoint, 'https://www.kaggle.com')
37 |         self.assertEqual(client.http_client()._verbose, False)
38 | 
39 | 
40 | if __name__ == '__main__':
41 |     unittest.main()
42 | 


--------------------------------------------------------------------------------
/kagglesdk/users/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/users/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/users/services/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/users/services/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/users/services/account_service.py:
--------------------------------------------------------------------------------
 1 | from kagglesdk.kaggle_http_client import KaggleHttpClient
 2 | from kagglesdk.users.types.account_service import GenerateAccessTokenRequest, GenerateAccessTokenResponse
 3 | 
 4 | 
 5 | class AccountClient(object):
 6 | 
 7 |     def __init__(self, client: KaggleHttpClient):
 8 |         self._client = client
 9 | 
10 |     def generate_access_token(self, request: GenerateAccessTokenRequest = None) -> GenerateAccessTokenResponse:
11 |         r"""
12 |         Args:
13 |           request (GenerateAccessTokenRequest):
14 |             The request object; initialized to empty instance if not specified.
15 |         """
16 | 
17 |         if request is None:
18 |             request = GenerateAccessTokenRequest()
19 | 
20 |         return self._client.call("users.AccountService", "GenerateAccessToken", request, GenerateAccessTokenResponse)
21 | 


--------------------------------------------------------------------------------
/kagglesdk/users/types/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/kagglesdk/users/types/__init__.py


--------------------------------------------------------------------------------
/kagglesdk/users/types/users_enums.py:
--------------------------------------------------------------------------------
 1 | import enum
 2 | 
 3 | 
 4 | class UserAchievementTier(enum.Enum):
 5 |     NOVICE = 0
 6 |     CONTRIBUTOR = 1
 7 |     EXPERT = 2
 8 |     MASTER = 3
 9 |     GRANDMASTER = 4
10 |     STAFF = 5
11 |     """Kaggle admins"""
12 |     ORGANIZATION = 11
13 |     """Organizations"""
14 |     RECALC = 21
15 |     """Flag user for tier recalculation"""
16 | 
17 | 
18 | class CollaboratorType(enum.Enum):
19 |     COLLABORATOR_TYPE_UNSPECIFIED = 0
20 |     READER = 1
21 |     WRITER = 2
22 |     OWNER = 3
23 |     ADMIN = 4
24 | 


--------------------------------------------------------------------------------
/pyproject.toml:
--------------------------------------------------------------------------------
 1 | [build-system]
 2 | requires = [
 3 |     "hatchling",
 4 | ]
 5 | build-backend = "hatchling.build"
 6 | 
 7 | [project]
 8 | name = "kaggle"
 9 | dynamic = [
10 |     "version",
11 | ]
12 | description = "Access Kaggle resources anywhere"
13 | authors = [
14 |     { name = "Kaggle", email = "support@kaggle.com" },
15 | ]
16 | license = { file = "LICENSE.txt" }
17 | readme = "README.md"
18 | classifiers = [
19 |     "Programming Language :: Python :: 3",
20 |     "License :: OSI Approved :: Apache Software License",
21 |     "Operating System :: OS Independent",
22 | ]
23 | keywords = ["Kaggle", "API"]
24 | requires-python = ">=3.7"
25 | dependencies = [
26 |     "bleach",
27 |     "certifi>=14.05.14",
28 |     "charset-normalizer",
29 |     "idna",
30 |     "python-dateutil>=2.5.3",
31 |     "python-slugify",
32 |     "requests",
33 |     "setuptools>=21.0.0",
34 |     "six>=1.10",
35 |     "text-unidecode",
36 |     "tqdm",
37 |     "urllib3>=1.15.1",
38 |     "webencodings",
39 |     "protobuf"
40 | ]
41 | 
42 | [project.scripts]
43 | kaggle = "kaggle.cli:main"
44 | 
45 | [project.urls]
46 | Homepage = "https://github.com/Kaggle/kaggle-api"
47 | Issues = "https://github.com/Kaggle/kaggle-api/issues"
48 | 
49 | [tool.hatch.version]
50 | path = "src/__init__.py"
51 | # TODO: Remove validate-bump = false for next stable release
52 | validate-bump = false
53 | 
54 | [tool.hatch.envs.default]
55 | dependencies = [
56 |     "pytest",
57 | ]
58 | 
59 | [tool.hatch.build.targets.wheel]
60 | packages = ["src/kaggle", "src/kagglesdk"]
61 | 
62 | [tool.hatch.envs.default.scripts]
63 | install-unzip = """sudo apt-get install -y unzip || echo 'unzip could not be installed'"""
64 | # TODO: install in Mac/Windows
65 | install-black = """pip3 install black --break-system-packages || echo 'black could not be installed'"""
66 | install-toml = """sudo apt-get install -y python3-toml || echo 'toml could not be installed'"""
67 | install-deps = "hatch run install-unzip && hatch run install-black && hatch run install-toml"
68 | 
69 | integration-test = "pytest {args:integration_tests}"
70 | 
71 | compile = "./tools/GeneratePythonLibrary.sh"
72 | install = "./tools/GeneratePythonLibrary.sh --install"
73 | watch = "./tools/GeneratePythonLibrary.sh --watch"
74 | test = "./tools/GeneratePythonLibrary.sh --test local"
75 | 
76 | [tool.docformatter]
77 | recursive = true
78 | 
79 | [tool.black]
80 | target-version = ["py39"]
81 | line-length = 120
82 | skip-string-normalization = true
83 | 


--------------------------------------------------------------------------------
/requirements.in:
--------------------------------------------------------------------------------
1 | certifi >= 14.05.14
2 | six >= 1.10
3 | python_dateutil >= 2.5.3
4 | urllib3 >= 1.15.1
5 | 


--------------------------------------------------------------------------------
/requirements.txt:
--------------------------------------------------------------------------------
 1 | #
 2 | # This file is autogenerated by pip-compile with Python 3.11
 3 | # by the following command:
 4 | #
 5 | #    pip-compile --allow-unsafe --generate-hashes requirements.in
 6 | #
 7 | certifi==2025.1.31 \
 8 |     --hash=sha256:3d5da6925056f6f18f119200434a4780a94263f10d1c21d032a6f6b2baa20651 \
 9 |     --hash=sha256:ca78db4565a652026a4db2bcdf68f2fb589ea80d0be70e03929ed730746b84fe
10 |     # via -r requirements.in
11 | python-dateutil==2.9.0.post0 \
12 |     --hash=sha256:37dd54208da7e1cd875388217d5e00ebd4179249f90fb72437e91a35459a0ad3 \
13 |     --hash=sha256:a8b2bc7bffae282281c8140a97d3aa9c14da0b136dfe83f850eea9a5f7470427
14 |     # via -r requirements.in
15 | six==1.17.0 \
16 |     --hash=sha256:4721f391ed90541fddacab5acf947aa0d3dc7d27b2e1e8eda2be8970586c3274 \
17 |     --hash=sha256:ff70335d468e7eb6ec65b95b99d3a2836546063f63acc5171de367e834932a81
18 |     # via
19 |     #   -r requirements.in
20 |     #   python-dateutil
21 | urllib3==2.3.0 \
22 |     --hash=sha256:1cee9ad369867bfdbbb48b7dd50374c0967a0bb7710050facf0dd6911440e3df \
23 |     --hash=sha256:f8c5449b3cf0861679ce7e0503c7b44b5ec981bec0d1d3795a07f1ba96f0204d
24 |     # via -r requirements.in
25 | 


--------------------------------------------------------------------------------
/setup.cfg:
--------------------------------------------------------------------------------
1 | [metadata]
2 | description-file = README.md


--------------------------------------------------------------------------------
/setup.py:
--------------------------------------------------------------------------------
 1 | # coding=utf-8
 2 | from setuptools import setup, find_packages
 3 | 
 4 | # Note: pyproject.toml seems to be chosen by pip install over setup.py, so this
 5 | # file should not be used anymore. However, cloudbuild.yaml still uses setup.py
 6 | # to drive the build that is published to pypi.org. That needs to be changed
 7 | # before this file can be removed. And, due to that, pyproject.toml needs to be
 8 | # deleted before a release can be made.
 9 | # https://packaging.python.org/en/latest/guides/modernize-setup-py-project/
10 | setup(
11 |     name='kaggle',
12 |     version='1.7.4.2',
13 |     description='Kaggle API',
14 |     long_description=(
15 |         'Official API for https://www.kaggle.com, accessible using a command line '
16 |         'tool implemented in Python. Beta release - Kaggle reserves the right to '
17 |         'modify the API functionality currently offered.'
18 |     ),
19 |     author='Kaggle',
20 |     author_email='support@kaggle.com',
21 |     url='https://github.com/Kaggle/kaggle-api',
22 |     project_urls={
23 |         'Documentation': 'https://www.kaggle.com/docs/api',
24 |         'GitHub': 'https://github.com/Kaggle/kaggle-api',
25 |         'Tracker': 'https://github.com/Kaggle/kaggle-api/issues',
26 |     },
27 |     keywords=['Kaggle', 'API'],
28 |     entry_points={'console_scripts': ['kaggle = kaggle.cli:main']},
29 |     install_requires=[
30 |         'six >= 1.10',
31 |         'certifi >= 2023.7.22',
32 |         'python-dateutil',
33 |         'requests',
34 |         'tqdm',
35 |         'python-slugify',
36 |         'urllib3',
37 |         'bleach',
38 |         'protobuf',
39 |         'hatchling >= 1.27.0',
40 |     ],
41 |     packages=find_packages(
42 |         where='src',
43 |         include=['kaggle*'],
44 |     ),
45 |     package_dir={"": "src"},
46 | )
47 | 


--------------------------------------------------------------------------------
/src/__init__.py:
--------------------------------------------------------------------------------
1 | __version__ = "1.7.4.2"
2 | 


--------------------------------------------------------------------------------
/src/kaggle/__init__.py:
--------------------------------------------------------------------------------
1 | # coding=utf-8
2 | from __future__ import absolute_import
3 | from kaggle.api.kaggle_api_extended import KaggleApi
4 | 
5 | api = KaggleApi()
6 | api.authenticate()
7 | 


--------------------------------------------------------------------------------
/src/kaggle/api/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kaggle/api/__init__.py


--------------------------------------------------------------------------------
/src/kaggle/models/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kaggle/models/__init__.py


--------------------------------------------------------------------------------
/src/kaggle/models/api_blob_type.py:
--------------------------------------------------------------------------------
1 | class ApiBlobType(object):
2 |     DATASET = "dataset"
3 |     MODEL = "model"
4 |     INBOX = "inbox"
5 | 


--------------------------------------------------------------------------------
/src/kaggle/models/model_instance_new_version_request.py:
--------------------------------------------------------------------------------
  1 | #!/usr/bin/python
  2 | #
  3 | # Copyright 2024 Kaggle Inc
  4 | #
  5 | # Licensed under the Apache License, Version 2.0 (the "License");
  6 | # you may not use this file except in compliance with the License.
  7 | # You may obtain a copy of the License at
  8 | #
  9 | #      http://www.apache.org/licenses/LICENSE-2.0
 10 | #
 11 | # Unless required by applicable law or agreed to in writing, software
 12 | # distributed under the License is distributed on an "AS IS" BASIS,
 13 | # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 14 | # See the License for the specific language governing permissions and
 15 | # limitations under the License.
 16 | 
 17 | # coding: utf-8
 18 | 
 19 | import pprint
 20 | import re  # noqa: F401
 21 | 
 22 | import six
 23 | 
 24 | from kaggle.models.upload_file import UploadFile  # noqa: F401,E501
 25 | 
 26 | 
 27 | class ModelInstanceNewVersionRequest(object):
 28 |     """
 29 |     Attributes:
 30 |       project_types (dict): The key is attribute name
 31 |                             and the value is attribute type.
 32 |       attribute_map (dict): The key is attribute name
 33 |                             and the value is json key in definition.
 34 |     """
 35 | 
 36 |     project_types = {'version_notes': 'str', 'files': 'list[UploadFile]'}
 37 | 
 38 |     attribute_map = {'version_notes': 'versionNotes', 'files': 'files'}
 39 | 
 40 |     def __init__(self, version_notes=None, files=None):  # noqa: E501
 41 | 
 42 |         self._version_notes = None
 43 |         self._files = None
 44 |         self.discriminator = None
 45 | 
 46 |         if version_notes is not None:
 47 |             self.version_notes = version_notes
 48 |         self.files = files
 49 | 
 50 |     @property
 51 |     def version_notes(self):
 52 |         """Gets the version_notes of this ModelInstanceNewVersionRequest.  #
 53 |         noqa: E501.
 54 | 
 55 |         The version notes for the model instance version  # noqa: E501
 56 | 
 57 |         :return: The version_notes of this
 58 |             ModelInstanceNewVersionRequest. # noqa: E501
 59 |         :rtype: str
 60 |         """
 61 |         return self._version_notes
 62 | 
 63 |     @version_notes.setter
 64 |     def version_notes(self, version_notes):
 65 |         """Sets the version_notes of this ModelInstanceNewVersionRequest.
 66 | 
 67 |         The version notes for the model instance version  # noqa: E501
 68 | 
 69 |         :param version_notes: The version_notes of this
 70 |             ModelInstanceNewVersionRequest. # noqa: E501
 71 |         :type: str
 72 |         """
 73 | 
 74 |         self._version_notes = version_notes
 75 | 
 76 |     @property
 77 |     def files(self):
 78 |         """Gets the files of this ModelInstanceNewVersionRequest.  # noqa:
 79 |         E501.
 80 | 
 81 |         A list of files that should be associated with the model
 82 |         instance version  # noqa: E501
 83 | 
 84 |         :return: The files of this ModelInstanceNewVersionRequest. #
 85 |             noqa: E501
 86 |         :rtype: list[UploadFile]
 87 |         """
 88 |         return self._files
 89 | 
 90 |     @files.setter
 91 |     def files(self, files):
 92 |         """Sets the files of this ModelInstanceNewVersionRequest.
 93 | 
 94 |         A list of files that should be associated with the model
 95 |         instance version  # noqa: E501
 96 | 
 97 |         :param files: The files of this ModelInstanceNewVersionRequest.
 98 |             # noqa: E501
 99 |         :type: list[UploadFile]
100 |         """
101 |         if files is None:
102 |             raise ValueError("Invalid value for `files`, must not be `None`")  # noqa: E501
103 | 
104 |         self._files = files
105 | 
106 |     def to_dict(self):
107 |         """Returns the model properties as a dict."""
108 |         result = {}
109 | 
110 |         for attr, _ in six.iteritems(self.project_types):
111 |             value = getattr(self, attr)
112 |             if isinstance(value, list):
113 |                 result[attr] = list(map(lambda x: x.to_dict() if hasattr(x, "to_dict") else x, value))
114 |             elif hasattr(value, "to_dict"):
115 |                 result[attr] = value.to_dict()
116 |             elif isinstance(value, dict):
117 |                 result[attr] = dict(
118 |                     map(
119 |                         lambda item: (item[0], item[1].to_dict()) if hasattr(item[1], "to_dict") else item,
120 |                         value.items(),
121 |                     )
122 |                 )
123 |             else:
124 |                 result[attr] = value
125 | 
126 |         return result
127 | 
128 |     def to_str(self):
129 |         """Returns the string representation of the model."""
130 |         return pprint.pformat(self.to_dict())
131 | 
132 |     def __repr__(self):
133 |         """For `print` and `pprint`"""
134 |         return self.to_str()
135 | 
136 |     def __eq__(self, other):
137 |         """Returns true if both objects are equal."""
138 |         if not isinstance(other, ModelInstanceNewVersionRequest):
139 |             return False
140 | 
141 |         return self.__dict__ == other.__dict__
142 | 
143 |     def __ne__(self, other):
144 |         """Returns true if both objects are not equal."""
145 |         return not self == other
146 | 


--------------------------------------------------------------------------------
/src/kaggle/models/start_blob_upload_response.py:
--------------------------------------------------------------------------------
  1 | #!/usr/bin/python
  2 | #
  3 | # Copyright 2024 Kaggle Inc
  4 | #
  5 | # Licensed under the Apache License, Version 2.0 (the "License");
  6 | # you may not use this file except in compliance with the License.
  7 | # You may obtain a copy of the License at
  8 | #
  9 | #      http://www.apache.org/licenses/LICENSE-2.0
 10 | #
 11 | # Unless required by applicable law or agreed to in writing, software
 12 | # distributed under the License is distributed on an "AS IS" BASIS,
 13 | # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 14 | # See the License for the specific language governing permissions and
 15 | # limitations under the License.
 16 | 
 17 | # coding: utf-8
 18 | 
 19 | import pprint
 20 | import re  # noqa: F401
 21 | 
 22 | import six
 23 | 
 24 | 
 25 | class StartBlobUploadResponse(object):
 26 |     """
 27 |     Attributes:
 28 |       project_types (dict): The key is attribute name
 29 |                             and the value is attribute type.
 30 |       attribute_map (dict): The key is attribute name
 31 |                             and the value is json key in definition.
 32 |     """
 33 | 
 34 |     project_types = {'token': 'str', 'create_url': 'str'}
 35 | 
 36 |     attribute_map = {'token': 'token', 'create_url': 'createUrl'}
 37 | 
 38 |     def __init__(self, token=None, create_url=None):  # noqa: E501
 39 |         """StartBlobUploadResponse - a model defined in Swagger"""  # noqa: E501
 40 | 
 41 |         self._token = None
 42 |         self._create_url = None
 43 |         self.discriminator = None
 44 | 
 45 |         self.token = token
 46 |         self.create_url = create_url
 47 | 
 48 |     @property
 49 |     def token(self):
 50 |         """Gets the token of this StartBlobUploadResponse.  # noqa: E501.
 51 | 
 52 |         Opaque string token used to reference the new blob/file.  # noqa:
 53 |         E501
 54 | 
 55 |         :return: The token of this StartBlobUploadResponse.  # noqa: E501
 56 |         :rtype: str
 57 |         """
 58 |         return self._token
 59 | 
 60 |     @token.setter
 61 |     def token(self, token):
 62 |         """Sets the token of this StartBlobUploadResponse.
 63 | 
 64 |         Opaque string token used to reference the new blob/file.  # noqa:
 65 |         E501
 66 | 
 67 |         :param token: The token of this StartBlobUploadResponse. # noqa:
 68 |             E501
 69 |         :type: str
 70 |         """
 71 |         if token is None:
 72 |             raise ValueError("Invalid value for `token`, must not be `None`")  # noqa: E501
 73 | 
 74 |         self._token = token
 75 | 
 76 |     @property
 77 |     def create_url(self):
 78 |         """Gets the create_url of this StartBlobUploadResponse.  # noqa: E501.
 79 | 
 80 |         URL to use to start the upload.  # noqa: E501
 81 | 
 82 |         :return: The create_url of this StartBlobUploadResponse. # noqa:
 83 |             E501
 84 |         :rtype: str
 85 |         """
 86 |         return self._create_url
 87 | 
 88 |     @create_url.setter
 89 |     def create_url(self, create_url):
 90 |         """Sets the create_url of this StartBlobUploadResponse.
 91 | 
 92 |         URL to use to start the upload.  # noqa: E501
 93 | 
 94 |         :param create_url: The create_url of this StartBlobUploadResponse. #
 95 |             noqa: E501
 96 |         :type: str
 97 |         """
 98 |         if create_url is None:
 99 |             raise ValueError("Invalid value for `create_url`, must not be `None`")  # noqa: E501
100 | 
101 |         self._create_url = create_url
102 | 
103 |     def to_dict(self):
104 |         """Returns the model properties as a dict."""
105 |         result = {}
106 | 
107 |         for attr, _ in six.iteritems(self.project_types):
108 |             value = getattr(self, attr)
109 |             if isinstance(value, list):
110 |                 result[attr] = list(map(lambda x: x.to_dict() if hasattr(x, "to_dict") else x, value))
111 |             elif hasattr(value, "to_dict"):
112 |                 result[attr] = value.to_dict()
113 |             elif isinstance(value, dict):
114 |                 result[attr] = dict(
115 |                     map(
116 |                         lambda item: (item[0], item[1].to_dict()) if hasattr(item[1], "to_dict") else item,
117 |                         value.items(),
118 |                     )
119 |                 )
120 |             else:
121 |                 result[attr] = value
122 | 
123 |         return result
124 | 
125 |     def to_str(self):
126 |         """Returns the string representation of the model."""
127 |         return pprint.pformat(self.to_dict())
128 | 
129 |     def __repr__(self):
130 |         """For `print` and `pprint`"""
131 |         return self.to_str()
132 | 
133 |     def __eq__(self, other):
134 |         """Returns true if both objects are equal."""
135 |         if not isinstance(other, StartBlobUploadResponse):
136 |             return False
137 | 
138 |         return self.__dict__ == other.__dict__
139 | 
140 |     def __ne__(self, other):
141 |         """Returns true if both objects are not equal."""
142 |         return not self == other
143 | 


--------------------------------------------------------------------------------
/src/kaggle/models/upload_file.py:
--------------------------------------------------------------------------------
  1 | #!/usr/bin/python
  2 | #
  3 | # Copyright 2024 Kaggle Inc
  4 | #
  5 | # Licensed under the Apache License, Version 2.0 (the "License");
  6 | # you may not use this file except in compliance with the License.
  7 | # You may obtain a copy of the License at
  8 | #
  9 | #      http://www.apache.org/licenses/LICENSE-2.0
 10 | #
 11 | # Unless required by applicable law or agreed to in writing, software
 12 | # distributed under the License is distributed on an "AS IS" BASIS,
 13 | # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 14 | # See the License for the specific language governing permissions and
 15 | # limitations under the License.
 16 | 
 17 | # coding: utf-8
 18 | 
 19 | import pprint
 20 | import re  # noqa: F401
 21 | 
 22 | import six
 23 | 
 24 | from kaggle.models.dataset_column import DatasetColumn  # noqa: F401,E501
 25 | 
 26 | 
 27 | class UploadFile(object):
 28 |     """
 29 |     Attributes:
 30 |       column_types (dict): The key is attribute name
 31 |                             and the value is attribute type.
 32 |       attribute_map (dict): The key is attribute name
 33 |                             and the value is json key in definition.
 34 |     """
 35 | 
 36 |     column_types = {'token': 'str', 'description': 'str', 'columns': 'list[DatasetColumn]'}
 37 | 
 38 |     attribute_map = {'token': 'token', 'description': 'description', 'columns': 'columns'}
 39 | 
 40 |     def __init__(self, token=None, description=None, columns=None):  # noqa: E501
 41 |         """UploadFile - a model defined in Swagger"""  # noqa: E501
 42 | 
 43 |         self._token = None
 44 |         self._description = None
 45 |         self._columns = None
 46 |         self.discriminator = None
 47 | 
 48 |         if token is not None:
 49 |             self.token = token
 50 |         if description is not None:
 51 |             self.description = description
 52 |         if columns is not None:
 53 |             self.columns = columns
 54 | 
 55 |     @property
 56 |     def token(self):
 57 |         """Gets the token of this UploadFile.  # noqa: E501.
 58 | 
 59 |         A token referencing a specific file upload that can be used across
 60 |         requests  # noqa: E501
 61 | 
 62 |         :return: The token of this UploadFile.  # noqa: E501
 63 |         :rtype: str
 64 |         """
 65 |         return self._token
 66 | 
 67 |     @token.setter
 68 |     def token(self, token):
 69 |         """Sets the token of this UploadFile.
 70 | 
 71 |         A token referencing a specific file upload that can be used across
 72 |         requests  # noqa: E501
 73 | 
 74 |         :param token: The token of this UploadFile.  # noqa: E501
 75 |         :type: str
 76 |         """
 77 | 
 78 |         self._token = token
 79 | 
 80 |     @property
 81 |     def description(self):
 82 |         """Gets the description of this UploadFile.  # noqa: E501.
 83 | 
 84 |         The file description  # noqa: E501
 85 | 
 86 |         :return: The description of this UploadFile.  # noqa: E501
 87 |         :rtype: str
 88 |         """
 89 |         return self._description
 90 | 
 91 |     @description.setter
 92 |     def description(self, description):
 93 |         """Sets the description of this UploadFile.
 94 | 
 95 |         The file description  # noqa: E501
 96 | 
 97 |         :param description: The description of this UploadFile. # noqa: E501
 98 |         :type: str
 99 |         """
100 | 
101 |         self._description = description
102 | 
103 |     @property
104 |     def columns(self):
105 |         """Gets the columns of this UploadFile.  # noqa: E501.
106 | 
107 |         A list of dataset column metadata  # noqa: E501
108 | 
109 |         :return: The columns of this UploadFile.  # noqa: E501
110 |         :rtype: list[DatasetColumn]
111 |         """
112 |         return self._columns
113 | 
114 |     @columns.setter
115 |     def columns(self, columns):
116 |         """Sets the columns of this UploadFile.
117 | 
118 |         A list of dataset column metadata  # noqa: E501
119 | 
120 |         :param columns: The columns of this UploadFile.  # noqa: E501
121 |         :type: list[DatasetColumn]
122 |         """
123 | 
124 |         self._columns = columns
125 | 
126 |     def to_dict(self):
127 |         """Returns the model properties as a dict."""
128 |         result = {}
129 | 
130 |         for attr, _ in six.iteritems(self.column_types):
131 |             value = getattr(self, attr)
132 |             if isinstance(value, list):
133 |                 result[attr] = list(map(lambda x: x.to_dict() if hasattr(x, "to_dict") else x, value))
134 |             elif hasattr(value, "to_dict"):
135 |                 result[attr] = value.to_dict()
136 |             elif isinstance(value, dict):
137 |                 result[attr] = dict(
138 |                     map(
139 |                         lambda item: (item[0], item[1].to_dict()) if hasattr(item[1], "to_dict") else item,
140 |                         value.items(),
141 |                     )
142 |                 )
143 |             else:
144 |                 result[attr] = value
145 | 
146 |         return result
147 | 
148 |     def to_str(self):
149 |         """Returns the string representation of the model."""
150 |         return pprint.pformat(self.to_dict())
151 | 
152 |     def __repr__(self):
153 |         """For `print` and `pprint`"""
154 |         return self.to_str()
155 | 
156 |     def __eq__(self, other):
157 |         """Returns true if both objects are equal."""
158 |         if not isinstance(other, UploadFile):
159 |             return False
160 | 
161 |         return self.__dict__ == other.__dict__
162 | 
163 |     def __ne__(self, other):
164 |         """Returns true if both objects are not equal."""
165 |         return not self == other
166 | 


--------------------------------------------------------------------------------
/src/kaggle/test/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kaggle/test/__init__.py


--------------------------------------------------------------------------------
/src/kaggle/test/test_authenticate.py:
--------------------------------------------------------------------------------
 1 | from kaggle.api.kaggle_api_extended import KaggleApi
 2 | 
 3 | # python -m unittest tests.test_authenticate
 4 | 
 5 | import os
 6 | import unittest
 7 | 
 8 | 
 9 | class TestAuthenticate(unittest.TestCase):
10 | 
11 |     def setUp(self):
12 |         print("setup             class:%s" % self)
13 | 
14 |     def tearDown(self):
15 |         print("teardown          class:TestStuff")
16 | 
17 |     # Environment
18 | 
19 |     def test_environment_variables(self):
20 |         os.environ['KAGGLE_USERNAME'] = 'dinosaur'
21 |         os.environ['KAGGLE_KEY'] = 'xxxxxxxxxxxx'
22 |         api = KaggleApi()
23 | 
24 |         # We haven't authenticated yet
25 |         self.assertTrue("key" not in api.config_values)
26 |         self.assertTrue("username" not in api.config_values)
27 |         api.authenticate()
28 | 
29 |         # Should be set from the environment
30 |         self.assertEqual(api.config_values['key'], 'xxxxxxxxxxxx')
31 |         self.assertEqual(api.config_values['username'], 'dinosaur')
32 | 
33 |     # Configuration Actions
34 | 
35 |     def test_config_actions(self):
36 |         api = KaggleApi()
37 | 
38 |         self.assertTrue(api.config_dir.endswith('kaggle'))
39 |         self.assertEqual(api.get_config_value('doesntexist'), None)
40 | 
41 | 
42 | if __name__ == '__main__':
43 |     unittest.main()
44 | 


--------------------------------------------------------------------------------
/src/kagglesdk/__init__.py:
--------------------------------------------------------------------------------
1 | from kagglesdk.kaggle_client import KaggleClient
2 | from kagglesdk.kaggle_env import KaggleEnv
3 | 


--------------------------------------------------------------------------------
/src/kagglesdk/admin/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/admin/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/admin/services/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/admin/services/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/admin/services/inbox_file_service.py:
--------------------------------------------------------------------------------
 1 | from kagglesdk.admin.types.inbox_file_service import CreateInboxFileRequest, CreateInboxFileResponse
 2 | from kagglesdk.kaggle_http_client import KaggleHttpClient
 3 | 
 4 | 
 5 | class InboxFileClient(object):
 6 |     """File drop/pickup functionality."""
 7 | 
 8 |     def __init__(self, client: KaggleHttpClient):
 9 |         self._client = client
10 | 
11 |     def create_inbox_file(self, request: CreateInboxFileRequest = None) -> CreateInboxFileResponse:
12 |         r"""
13 |         Creates (aka 'drops') a new file into the inbox.
14 | 
15 |         Args:
16 |           request (CreateInboxFileRequest):
17 |             The request object; initialized to empty instance if not specified.
18 |         """
19 | 
20 |         if request is None:
21 |             request = CreateInboxFileRequest()
22 | 
23 |         return self._client.call("admin.InboxFileService", "CreateInboxFile", request, CreateInboxFileResponse)
24 | 


--------------------------------------------------------------------------------
/src/kagglesdk/admin/types/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/admin/types/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/admin/types/inbox_file_service.py:
--------------------------------------------------------------------------------
 1 | from kagglesdk.kaggle_object import *
 2 | 
 3 | 
 4 | class CreateInboxFileRequest(KaggleObject):
 5 |     r"""
 6 |     Attributes:
 7 |       virtual_directory (str)
 8 |         Directory name used for tagging the uploaded file.
 9 |       blob_file_token (str)
10 |         Token representing the uploaded file.
11 |     """
12 | 
13 |     def __init__(self):
14 |         self._virtual_directory = ""
15 |         self._blob_file_token = ""
16 |         self._freeze()
17 | 
18 |     @property
19 |     def virtual_directory(self) -> str:
20 |         """Directory name used for tagging the uploaded file."""
21 |         return self._virtual_directory
22 | 
23 |     @virtual_directory.setter
24 |     def virtual_directory(self, virtual_directory: str):
25 |         if virtual_directory is None:
26 |             del self.virtual_directory
27 |             return
28 |         if not isinstance(virtual_directory, str):
29 |             raise TypeError('virtual_directory must be of type str')
30 |         self._virtual_directory = virtual_directory
31 | 
32 |     @property
33 |     def blob_file_token(self) -> str:
34 |         """Token representing the uploaded file."""
35 |         return self._blob_file_token
36 | 
37 |     @blob_file_token.setter
38 |     def blob_file_token(self, blob_file_token: str):
39 |         if blob_file_token is None:
40 |             del self.blob_file_token
41 |             return
42 |         if not isinstance(blob_file_token, str):
43 |             raise TypeError('blob_file_token must be of type str')
44 |         self._blob_file_token = blob_file_token
45 | 
46 |     def endpoint(self):
47 |         path = '/api/v1/inbox/files/create'
48 |         return path.format_map(self.to_field_map(self))
49 | 
50 |     @staticmethod
51 |     def method():
52 |         return 'POST'
53 | 
54 |     @staticmethod
55 |     def body_fields():
56 |         return '*'
57 | 
58 | 
59 | class CreateInboxFileResponse(KaggleObject):
60 |     r"""
61 |     NOTE: This is sent to non-admins, so we're intentionally *NOT* sending back
62 |     the full InboxFile (with its URL for a direct download).
63 | 
64 |     """
65 | 
66 |     pass
67 | 
68 | 
69 | CreateInboxFileRequest._fields = [
70 |     FieldMetadata("virtualDirectory", "virtual_directory", "_virtual_directory", str, "", PredefinedSerializer()),
71 |     FieldMetadata("blobFileToken", "blob_file_token", "_blob_file_token", str, "", PredefinedSerializer()),
72 | ]
73 | 
74 | CreateInboxFileResponse._fields = []
75 | 


--------------------------------------------------------------------------------
/src/kagglesdk/blobs/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/blobs/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/blobs/services/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/blobs/services/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/blobs/services/blob_api_service.py:
--------------------------------------------------------------------------------
 1 | from kagglesdk.blobs.types.blob_api_service import ApiStartBlobUploadRequest, ApiStartBlobUploadResponse
 2 | from kagglesdk.kaggle_http_client import KaggleHttpClient
 3 | 
 4 | 
 5 | class BlobApiClient(object):
 6 |     r"""
 7 |     Binary Large OBject (BLOB) service used for uploading files to Google Cloud
 8 |     Storage (GCS).
 9 |     """
10 | 
11 |     def __init__(self, client: KaggleHttpClient):
12 |         self._client = client
13 | 
14 |     def start_blob_upload(self, request: ApiStartBlobUploadRequest = None) -> ApiStartBlobUploadResponse:
15 |         r"""
16 |         Starts a blob upload (i.e. reserves a spot for the upload on GCS).
17 | 
18 |         Args:
19 |           request (ApiStartBlobUploadRequest):
20 |             The request object; initialized to empty instance if not specified.
21 |         """
22 | 
23 |         if request is None:
24 |             request = ApiStartBlobUploadRequest()
25 | 
26 |         return self._client.call("blobs.BlobApiService", "ApiStartBlobUpload", request, ApiStartBlobUploadResponse)
27 | 


--------------------------------------------------------------------------------
/src/kagglesdk/blobs/types/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/blobs/types/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/common/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/common/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/common/types/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/common/types/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/common/types/file_download.py:
--------------------------------------------------------------------------------
  1 | from kagglesdk.kaggle_object import *
  2 | from typing import Optional
  3 | 
  4 | 
  5 | class FileDownload(KaggleObject):
  6 |     r"""
  7 |     Standard response object representing a file download.
  8 |     See http://go/kaggle-proto-handler-file-downloads
  9 |     Some field names/descriptions borrowed from
 10 |     google3/gdata/rosy/proto/data.proto
 11 | 
 12 |     Attributes:
 13 |       content_type (str)
 14 |         MIME type of the data
 15 |         TODO(aip.dev/143): (-- api-linter: core::0143::standardized-codes=disabled
 16 |         --)
 17 |       file_name (str)
 18 |         Original file name
 19 |       token (str)
 20 |         A unique fingerprint for the file/media data
 21 |       content_length (int)
 22 |         Size of the data, in bytes (if known)
 23 |     """
 24 | 
 25 |     def __init__(self):
 26 |         self._content_type = ""
 27 |         self._file_name = ""
 28 |         self._token = ""
 29 |         self._content_length = None
 30 |         self._freeze()
 31 | 
 32 |     @property
 33 |     def content_type(self) -> str:
 34 |         r"""
 35 |         MIME type of the data
 36 |         TODO(aip.dev/143): (-- api-linter: core::0143::standardized-codes=disabled
 37 |         --)
 38 |         """
 39 |         return self._content_type
 40 | 
 41 |     @content_type.setter
 42 |     def content_type(self, content_type: str):
 43 |         if content_type is None:
 44 |             del self.content_type
 45 |             return
 46 |         if not isinstance(content_type, str):
 47 |             raise TypeError('content_type must be of type str')
 48 |         self._content_type = content_type
 49 | 
 50 |     @property
 51 |     def file_name(self) -> str:
 52 |         """Original file name"""
 53 |         return self._file_name
 54 | 
 55 |     @file_name.setter
 56 |     def file_name(self, file_name: str):
 57 |         if file_name is None:
 58 |             del self.file_name
 59 |             return
 60 |         if not isinstance(file_name, str):
 61 |             raise TypeError('file_name must be of type str')
 62 |         self._file_name = file_name
 63 | 
 64 |     @property
 65 |     def token(self) -> str:
 66 |         """A unique fingerprint for the file/media data"""
 67 |         return self._token
 68 | 
 69 |     @token.setter
 70 |     def token(self, token: str):
 71 |         if token is None:
 72 |             del self.token
 73 |             return
 74 |         if not isinstance(token, str):
 75 |             raise TypeError('token must be of type str')
 76 |         self._token = token
 77 | 
 78 |     @property
 79 |     def content_length(self) -> int:
 80 |         """Size of the data, in bytes (if known)"""
 81 |         return self._content_length or 0
 82 | 
 83 |     @content_length.setter
 84 |     def content_length(self, content_length: int):
 85 |         if content_length is None:
 86 |             del self.content_length
 87 |             return
 88 |         if not isinstance(content_length, int):
 89 |             raise TypeError('content_length must be of type int')
 90 |         self._content_length = content_length
 91 | 
 92 |     @classmethod
 93 |     def prepare_from(cls, http_response):
 94 |         return http_response
 95 | 
 96 | 
 97 | FileDownload._fields = [
 98 |     FieldMetadata("contentType", "content_type", "_content_type", str, "", PredefinedSerializer()),
 99 |     FieldMetadata("fileName", "file_name", "_file_name", str, "", PredefinedSerializer()),
100 |     FieldMetadata("token", "token", "_token", str, "", PredefinedSerializer()),
101 |     FieldMetadata(
102 |         "contentLength", "content_length", "_content_length", int, None, PredefinedSerializer(), optional=True
103 |     ),
104 | ]
105 | 


--------------------------------------------------------------------------------
/src/kagglesdk/common/types/http_redirect.py:
--------------------------------------------------------------------------------
  1 | from datetime import timedelta
  2 | from kagglesdk.kaggle_object import *
  3 | from typing import Optional
  4 | 
  5 | 
  6 | class HttpRedirect(KaggleObject):
  7 |     r"""
  8 |     Represents an HTTP redirect (e.g. 301 or 302) response.
  9 |     Patterned after ASP.NET MVC's RedirectResult.
 10 | 
 11 |     Attributes:
 12 |       url (str)
 13 |         Destination URL for the redirect.
 14 |       permanent (bool)
 15 |         Should it be an HTTP 301 (permanent) redirect or just temporary (HTTP
 16 |         302)?.
 17 |       bypass_encoding (bool)
 18 |         When `true`, the `url` is already encoded, so bypass `UriHelper.Encode`.
 19 |         Otherwise, invoke `UriHelper.Encode` on the `url` before returning to the
 20 |         client.
 21 |       expiry (timedelta)
 22 |         Specifies how long the redirected url can be cached.
 23 |     """
 24 | 
 25 |     def __init__(self):
 26 |         self._url = ""
 27 |         self._permanent = False
 28 |         self._bypass_encoding = None
 29 |         self._expiry = None
 30 |         self._freeze()
 31 | 
 32 |     @property
 33 |     def url(self) -> str:
 34 |         """Destination URL for the redirect."""
 35 |         return self._url
 36 | 
 37 |     @url.setter
 38 |     def url(self, url: str):
 39 |         if url is None:
 40 |             del self.url
 41 |             return
 42 |         if not isinstance(url, str):
 43 |             raise TypeError('url must be of type str')
 44 |         self._url = url
 45 | 
 46 |     @property
 47 |     def permanent(self) -> bool:
 48 |         r"""
 49 |         Should it be an HTTP 301 (permanent) redirect or just temporary (HTTP
 50 |         302)?.
 51 |         """
 52 |         return self._permanent
 53 | 
 54 |     @permanent.setter
 55 |     def permanent(self, permanent: bool):
 56 |         if permanent is None:
 57 |             del self.permanent
 58 |             return
 59 |         if not isinstance(permanent, bool):
 60 |             raise TypeError('permanent must be of type bool')
 61 |         self._permanent = permanent
 62 | 
 63 |     @property
 64 |     def bypass_encoding(self) -> bool:
 65 |         r"""
 66 |         When `true`, the `url` is already encoded, so bypass `UriHelper.Encode`.
 67 |         Otherwise, invoke `UriHelper.Encode` on the `url` before returning to the
 68 |         client.
 69 |         """
 70 |         return self._bypass_encoding or False
 71 | 
 72 |     @bypass_encoding.setter
 73 |     def bypass_encoding(self, bypass_encoding: bool):
 74 |         if bypass_encoding is None:
 75 |             del self.bypass_encoding
 76 |             return
 77 |         if not isinstance(bypass_encoding, bool):
 78 |             raise TypeError('bypass_encoding must be of type bool')
 79 |         self._bypass_encoding = bypass_encoding
 80 | 
 81 |     @property
 82 |     def expiry(self) -> timedelta:
 83 |         """Specifies how long the redirected url can be cached."""
 84 |         return self._expiry
 85 | 
 86 |     @expiry.setter
 87 |     def expiry(self, expiry: timedelta):
 88 |         if expiry is None:
 89 |             del self.expiry
 90 |             return
 91 |         if not isinstance(expiry, timedelta):
 92 |             raise TypeError('expiry must be of type timedelta')
 93 |         self._expiry = expiry
 94 | 
 95 |     @classmethod
 96 |     def prepare_from(cls, http_response):
 97 |         return http_response
 98 | 
 99 | 
100 | HttpRedirect._fields = [
101 |     FieldMetadata("url", "url", "_url", str, "", PredefinedSerializer()),
102 |     FieldMetadata("permanent", "permanent", "_permanent", bool, False, PredefinedSerializer()),
103 |     FieldMetadata(
104 |         "bypassEncoding", "bypass_encoding", "_bypass_encoding", bool, None, PredefinedSerializer(), optional=True
105 |     ),
106 |     FieldMetadata("expiry", "expiry", "_expiry", timedelta, None, TimeDeltaSerializer()),
107 | ]
108 | 


--------------------------------------------------------------------------------
/src/kagglesdk/competitions/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/competitions/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/competitions/services/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/competitions/services/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/competitions/types/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/competitions/types/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/competitions/types/competition_enums.py:
--------------------------------------------------------------------------------
 1 | import enum
 2 | 
 3 | 
 4 | class CompetitionListTab(enum.Enum):
 5 |     COMPETITION_LIST_TAB_GENERAL = 0
 6 |     """TODO(aip.dev/126): (-- api-linter: core::0126::unspecified=disabled --)"""
 7 |     COMPETITION_LIST_TAB_ENTERED = 1
 8 |     COMPETITION_LIST_TAB_COMMUNITY = 2
 9 |     COMPETITION_LIST_TAB_HOSTED = 3
10 |     COMPETITION_LIST_TAB_UNLAUNCHED = 4
11 |     COMPETITION_LIST_TAB_UNLAUNCHED_COMMUNITY = 5
12 |     COMPETITION_LIST_TAB_EVERYTHING = 6
13 | 
14 | 
15 | class CompetitionSortBy(enum.Enum):
16 |     COMPETITION_SORT_BY_GROUPED = 0
17 |     """TODO(aip.dev/126): (-- api-linter: core::0126::unspecified=disabled --)"""
18 |     COMPETITION_SORT_BY_BEST = 1
19 |     COMPETITION_SORT_BY_PRIZE = 2
20 |     COMPETITION_SORT_BY_EARLIEST_DEADLINE = 3
21 |     COMPETITION_SORT_BY_LATEST_DEADLINE = 4
22 |     COMPETITION_SORT_BY_NUMBER_OF_TEAMS = 5
23 |     COMPETITION_SORT_BY_RELEVANCE = 6
24 |     COMPETITION_SORT_BY_RECENTLY_CREATED = 7
25 | 
26 | 
27 | class HostSegment(enum.Enum):
28 |     r"""
29 |     NOTE: Keep in Sync with Kaggle.Entities.HostSegment until migrated! Also keep
30 |     the comment in
31 |     competition_service.ListCompetitionsRequest.Selector.host_segment_id_filter
32 |     up to date
33 |     """
34 | 
35 |     HOST_SEGMENT_UNSPECIFIED = 0
36 |     HOST_SEGMENT_FEATURED = 1
37 |     HOST_SEGMENT_GETTING_STARTED = 5
38 |     HOST_SEGMENT_MASTERS = 6
39 |     HOST_SEGMENT_PLAYGROUND = 8
40 |     HOST_SEGMENT_RECRUITMENT = 3
41 |     HOST_SEGMENT_RESEARCH = 2
42 |     HOST_SEGMENT_COMMUNITY = 10
43 |     HOST_SEGMENT_ANALYTICS = 11
44 | 
45 | 
46 | class SubmissionGroup(enum.Enum):
47 |     SUBMISSION_GROUP_ALL = 0
48 |     """TODO(aip.dev/126): (-- api-linter: core::0126::unspecified=disabled --)"""
49 |     SUBMISSION_GROUP_SUCCESSFUL = 1
50 |     SUBMISSION_GROUP_SELECTED = 2
51 | 
52 | 
53 | class SubmissionSortBy(enum.Enum):
54 |     SUBMISSION_SORT_BY_DATE = 0
55 |     """TODO(aip.dev/126): (-- api-linter: core::0126::unspecified=disabled --)"""
56 |     SUBMISSION_SORT_BY_NAME = 1
57 |     SUBMISSION_SORT_BY_PRIVATE_SCORE = 2
58 |     SUBMISSION_SORT_BY_PUBLIC_SCORE = 3
59 | 


--------------------------------------------------------------------------------
/src/kagglesdk/competitions/types/submission_status.py:
--------------------------------------------------------------------------------
 1 | import enum
 2 | 
 3 | 
 4 | class SubmissionStatus(enum.Enum):
 5 |     """TODO(aip.dev/216): (-- api-linter: core::0216::synonyms=disabled --)"""
 6 | 
 7 |     PENDING = 0
 8 |     """TODO(aip.dev/126): (-- api-linter: core::0126::unspecified=disabled --)"""
 9 |     COMPLETE = 1
10 |     ERROR = 2
11 | 


--------------------------------------------------------------------------------
/src/kagglesdk/datasets/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/datasets/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/datasets/services/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/datasets/services/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/datasets/types/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/datasets/types/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/datasets/types/dataset_enums.py:
--------------------------------------------------------------------------------
 1 | import enum
 2 | 
 3 | 
 4 | class DatabundleVersionStatus(enum.Enum):
 5 |     NOT_YET_PERSISTED = 0
 6 |     BLOBS_RECEIVED = 1
 7 |     BLOBS_DECOMPRESSED = 2
 8 |     BLOBS_COPIED_TO_SDS = 3
 9 |     INDIVIDUAL_BLOBS_COMPRESSED = 4
10 |     READY = 5
11 |     FAILED = 6
12 |     DELETED = 7
13 |     REPROCESSING = 8
14 | 
15 | 
16 | class DatasetFileTypeGroup(enum.Enum):
17 |     r"""
18 |     This enum drives acceptable values from the python API, so avoid changing
19 |     enum member names if possible
20 |     """
21 | 
22 |     DATASET_FILE_TYPE_GROUP_ALL = 0
23 |     DATASET_FILE_TYPE_GROUP_CSV = 1
24 |     DATASET_FILE_TYPE_GROUP_SQLITE = 2
25 |     DATASET_FILE_TYPE_GROUP_JSON = 3
26 |     DATASET_FILE_TYPE_GROUP_BIG_QUERY = 4
27 | 
28 | 
29 | class DatasetLicenseGroup(enum.Enum):
30 |     r"""
31 |     This enum drives acceptable values from the python API, so avoid changing
32 |     enum member names if possible
33 |     """
34 | 
35 |     DATASET_LICENSE_GROUP_ALL = 0
36 |     DATASET_LICENSE_GROUP_CC = 1
37 |     DATASET_LICENSE_GROUP_GPL = 2
38 |     DATASET_LICENSE_GROUP_ODB = 3
39 |     DATASET_LICENSE_GROUP_OTHER = 4
40 | 
41 | 
42 | class DatasetSelectionGroup(enum.Enum):
43 |     DATASET_SELECTION_GROUP_PUBLIC = 0
44 |     DATASET_SELECTION_GROUP_MY = 1
45 |     DATASET_SELECTION_GROUP_USER = 2
46 |     DATASET_SELECTION_GROUP_USER_SHARED_WITH_ME = 3
47 |     DATASET_SELECTION_GROUP_UPVOTED = 4
48 |     DATASET_SELECTION_GROUP_MY_PRIVATE = 5
49 |     DATASET_SELECTION_GROUP_MY_PUBLIC = 10
50 |     DATASET_SELECTION_GROUP_ORGANIZATION = 6
51 |     DATASET_SELECTION_GROUP_BOOKMARKED = 11
52 |     DATASET_SELECTION_GROUP_COLLABORATION = 12
53 |     DATASET_SELECTION_GROUP_SHARED_WITH_USER = 13
54 |     DATASET_SELECTION_GROUP_FEATURED = 7
55 |     """Old"""
56 |     DATASET_SELECTION_GROUP_ALL = 8
57 |     DATASET_SELECTION_GROUP_UNFEATURED = 9
58 | 
59 | 
60 | class DatasetSizeGroup(enum.Enum):
61 |     r"""
62 |     This enum drives acceptable values from the python API, so avoid changing
63 |     enum member names if possible
64 |     """
65 | 
66 |     DATASET_SIZE_GROUP_ALL = 0
67 |     DATASET_SIZE_GROUP_SMALL = 1
68 |     DATASET_SIZE_GROUP_MEDIUM = 2
69 |     DATASET_SIZE_GROUP_LARGE = 3
70 | 
71 | 
72 | class DatasetSortBy(enum.Enum):
73 |     r"""
74 |     This enum drives acceptable values from the python API, so avoid changing
75 |     enum member names if possible
76 |     """
77 | 
78 |     DATASET_SORT_BY_HOTTEST = 0
79 |     DATASET_SORT_BY_VOTES = 1
80 |     DATASET_SORT_BY_UPDATED = 2
81 |     DATASET_SORT_BY_ACTIVE = 3
82 |     """Deprecated"""
83 |     DATASET_SORT_BY_PUBLISHED = 4
84 |     DATASET_SORT_BY_RELEVANCE = 5
85 |     """Old world"""
86 |     DATASET_SORT_BY_LAST_VIEWED = 6
87 |     DATASET_SORT_BY_USABILITY = 7
88 | 
89 | 
90 | class DatasetViewedGroup(enum.Enum):
91 |     DATASET_VIEWED_GROUP_UNSPECIFIED = 0
92 |     DATASET_VIEWED_GROUP_VIEWED = 1
93 | 


--------------------------------------------------------------------------------
/src/kagglesdk/education/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/education/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/education/services/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/education/services/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/education/services/education_api_service.py:
--------------------------------------------------------------------------------
 1 | from kagglesdk.education.types.education_api_service import (
 2 |     ApiTrackExerciseInteractionRequest,
 3 |     ApiTrackExerciseInteractionResponse,
 4 | )
 5 | from kagglesdk.kaggle_http_client import KaggleHttpClient
 6 | 
 7 | 
 8 | class EducationApiClient(object):
 9 | 
10 |     def __init__(self, client: KaggleHttpClient):
11 |         self._client = client
12 | 
13 |     def track_exercise_interaction(
14 |         self, request: ApiTrackExerciseInteractionRequest = None
15 |     ) -> ApiTrackExerciseInteractionResponse:
16 |         r"""
17 |         Args:
18 |           request (ApiTrackExerciseInteractionRequest):
19 |             The request object; initialized to empty instance if not specified.
20 |         """
21 | 
22 |         if request is None:
23 |             request = ApiTrackExerciseInteractionRequest()
24 | 
25 |         return self._client.call(
26 |             "education.EducationApiService", "ApiTrackExerciseInteraction", request, ApiTrackExerciseInteractionResponse
27 |         )
28 | 


--------------------------------------------------------------------------------
/src/kagglesdk/education/types/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/education/types/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/education/types/education_service.py:
--------------------------------------------------------------------------------
  1 | import enum
  2 | from kagglesdk.kaggle_object import *
  3 | from typing import Optional
  4 | 
  5 | 
  6 | class LearnExerciseInteractionType(enum.Enum):
  7 |     LEARN_EXERCISE_INTERACTION_TYPE_UNSPECIFIED = 0
  8 |     CHECK = 1
  9 |     HINT = 2
 10 |     SOLUTION = 3
 11 | 
 12 | 
 13 | class LearnExerciseOutcomeType(enum.Enum):
 14 |     LEARN_EXERCISE_OUTCOME_TYPE_UNSPECIFIED = 0
 15 |     PASS = 1
 16 |     FAIL = 2
 17 |     EXCEPTION = 3
 18 |     UNATTEMPTED = 4
 19 | 
 20 | 
 21 | class LearnExerciseQuestionType(enum.Enum):
 22 |     LEARN_EXERCISE_QUESTION_TYPE_UNSPECIFIED = 0
 23 |     EQUALITY_CHECK_PROBLEM = 1
 24 |     CODING_PROBLEM = 2
 25 |     FUNCTION_PROBLEM = 3
 26 |     THOUGHT_EXPERIMENT = 4
 27 | 
 28 | 
 29 | class LearnNudgeType(enum.Enum):
 30 |     COURSE_COMPLETE_NO_BONUS_LESSONS = 0
 31 |     COURSE_COMPLETE_WITH_BONUS_LESSONS = 1
 32 |     COURSE_INCOMPLETE = 2
 33 |     DO_EXERCISE = 3
 34 |     DO_TUTORIAL = 4
 35 | 
 36 | 
 37 | class LearnNudge(KaggleObject):
 38 |     r"""
 39 |     Attributes:
 40 |       course_index (int)
 41 |       course_name (str)
 42 |       course_slug (str)
 43 |       next_item_name (str)
 44 |       next_item_url (str)
 45 |       next_item_type (LearnNudgeType)
 46 |     """
 47 | 
 48 |     def __init__(self):
 49 |         self._course_index = 0
 50 |         self._course_name = ""
 51 |         self._course_slug = ""
 52 |         self._next_item_name = ""
 53 |         self._next_item_url = ""
 54 |         self._next_item_type = LearnNudgeType.COURSE_COMPLETE_NO_BONUS_LESSONS
 55 |         self._freeze()
 56 | 
 57 |     @property
 58 |     def course_index(self) -> int:
 59 |         return self._course_index
 60 | 
 61 |     @course_index.setter
 62 |     def course_index(self, course_index: int):
 63 |         if course_index is None:
 64 |             del self.course_index
 65 |             return
 66 |         if not isinstance(course_index, int):
 67 |             raise TypeError('course_index must be of type int')
 68 |         self._course_index = course_index
 69 | 
 70 |     @property
 71 |     def course_name(self) -> str:
 72 |         return self._course_name
 73 | 
 74 |     @course_name.setter
 75 |     def course_name(self, course_name: str):
 76 |         if course_name is None:
 77 |             del self.course_name
 78 |             return
 79 |         if not isinstance(course_name, str):
 80 |             raise TypeError('course_name must be of type str')
 81 |         self._course_name = course_name
 82 | 
 83 |     @property
 84 |     def course_slug(self) -> str:
 85 |         return self._course_slug
 86 | 
 87 |     @course_slug.setter
 88 |     def course_slug(self, course_slug: str):
 89 |         if course_slug is None:
 90 |             del self.course_slug
 91 |             return
 92 |         if not isinstance(course_slug, str):
 93 |             raise TypeError('course_slug must be of type str')
 94 |         self._course_slug = course_slug
 95 | 
 96 |     @property
 97 |     def next_item_name(self) -> str:
 98 |         return self._next_item_name
 99 | 
100 |     @next_item_name.setter
101 |     def next_item_name(self, next_item_name: str):
102 |         if next_item_name is None:
103 |             del self.next_item_name
104 |             return
105 |         if not isinstance(next_item_name, str):
106 |             raise TypeError('next_item_name must be of type str')
107 |         self._next_item_name = next_item_name
108 | 
109 |     @property
110 |     def next_item_url(self) -> str:
111 |         return self._next_item_url
112 | 
113 |     @next_item_url.setter
114 |     def next_item_url(self, next_item_url: str):
115 |         if next_item_url is None:
116 |             del self.next_item_url
117 |             return
118 |         if not isinstance(next_item_url, str):
119 |             raise TypeError('next_item_url must be of type str')
120 |         self._next_item_url = next_item_url
121 | 
122 |     @property
123 |     def next_item_type(self) -> 'LearnNudgeType':
124 |         return self._next_item_type
125 | 
126 |     @next_item_type.setter
127 |     def next_item_type(self, next_item_type: 'LearnNudgeType'):
128 |         if next_item_type is None:
129 |             del self.next_item_type
130 |             return
131 |         if not isinstance(next_item_type, LearnNudgeType):
132 |             raise TypeError('next_item_type must be of type LearnNudgeType')
133 |         self._next_item_type = next_item_type
134 | 
135 | 
136 | LearnNudge._fields = [
137 |     FieldMetadata("courseIndex", "course_index", "_course_index", int, 0, PredefinedSerializer()),
138 |     FieldMetadata("courseName", "course_name", "_course_name", str, "", PredefinedSerializer()),
139 |     FieldMetadata("courseSlug", "course_slug", "_course_slug", str, "", PredefinedSerializer()),
140 |     FieldMetadata("nextItemName", "next_item_name", "_next_item_name", str, "", PredefinedSerializer()),
141 |     FieldMetadata("nextItemUrl", "next_item_url", "_next_item_url", str, "", PredefinedSerializer()),
142 |     FieldMetadata(
143 |         "nextItemType",
144 |         "next_item_type",
145 |         "_next_item_type",
146 |         LearnNudgeType,
147 |         LearnNudgeType.COURSE_COMPLETE_NO_BONUS_LESSONS,
148 |         EnumSerializer(),
149 |     ),
150 | ]
151 | 


--------------------------------------------------------------------------------
/src/kagglesdk/kaggle_client.py:
--------------------------------------------------------------------------------
 1 | from kagglesdk.kernels.services.kernels_api_service import KernelsApiClient
 2 | from kagglesdk.blobs.services.blob_api_service import BlobApiClient
 3 | from kagglesdk.education.services.education_api_service import EducationApiClient
 4 | from kagglesdk.models.services.model_api_service import ModelApiClient
 5 | from kagglesdk.models.services.model_service import ModelClient
 6 | from kagglesdk.competitions.services.competition_api_service import CompetitionApiClient
 7 | from kagglesdk.datasets.services.dataset_api_service import DatasetApiClient
 8 | from kagglesdk.admin.services.inbox_file_service import InboxFileClient
 9 | from kagglesdk.security.services.oauth_service import OAuthClient
10 | from kagglesdk.users.services.account_service import AccountClient
11 | from kagglesdk.kaggle_env import KaggleEnv
12 | from kagglesdk.kaggle_http_client import KaggleHttpClient
13 | 
14 | 
15 | class KaggleClient(object):
16 |     class Kernels(object):
17 |         def __init__(self, http_client: KaggleHttpClient):
18 |             self.kernels_api_client = KernelsApiClient(http_client)
19 | 
20 |     class Blobs(object):
21 |         def __init__(self, http_client: KaggleHttpClient):
22 |             self.blob_api_client = BlobApiClient(http_client)
23 | 
24 |     class Education(object):
25 |         def __init__(self, http_client: KaggleHttpClient):
26 |             self.education_api_client = EducationApiClient(http_client)
27 | 
28 |     class Models(object):
29 |         def __init__(self, http_client: KaggleHttpClient):
30 |             self.model_api_client = ModelApiClient(http_client)
31 |             self.model_client = ModelClient(http_client)
32 | 
33 |     class Competitions(object):
34 |         def __init__(self, http_client: KaggleHttpClient):
35 |             self.competition_api_client = CompetitionApiClient(http_client)
36 | 
37 |     class Datasets(object):
38 |         def __init__(self, http_client: KaggleHttpClient):
39 |             self.dataset_api_client = DatasetApiClient(http_client)
40 | 
41 |     class Admin(object):
42 |         def __init__(self, http_client: KaggleHttpClient):
43 |             self.inbox_file_client = InboxFileClient(http_client)
44 | 
45 |     class Security(object):
46 |         def __init__(self, http_client: KaggleHttpClient):
47 |             self.oauth_client = OAuthClient(http_client)
48 | 
49 |     class Users(object):
50 |         def __init__(self, http_client: KaggleHttpClient):
51 |             self.account_client = AccountClient(http_client)
52 | 
53 |     def __init__(self, env: KaggleEnv = None, verbose: bool = False, username: str = None, password: str = None):
54 |         self._http_client = http_client = KaggleHttpClient(
55 |             env, verbose, self._renew_iap_token, username=username, password=password
56 |         )
57 |         self.kernels = KaggleClient.Kernels(http_client)
58 |         self.blobs = KaggleClient.Blobs(http_client)
59 |         self.education = KaggleClient.Education(http_client)
60 |         self.models = KaggleClient.Models(http_client)
61 |         self.competitions = KaggleClient.Competitions(http_client)
62 |         self.datasets = KaggleClient.Datasets(http_client)
63 |         self.admin = KaggleClient.Admin(http_client)
64 |         self.security = KaggleClient.Security(http_client)
65 |         self.users = KaggleClient.Users(http_client)
66 |         self.username = username
67 |         self.password = password
68 | 
69 |     def http_client(self):
70 |         return self._http_client
71 | 
72 |     def _renew_iap_token(self):
73 |         return self.admin.admin_client.renew_iap_token()
74 | 
75 |     def __enter__(self):
76 |         self._http_client.__enter__()
77 |         return self
78 | 
79 |     def __exit__(self, exc_type, exc_value, tb):
80 |         self._http_client.__exit__(exc_type, exc_value, tb)
81 | 


--------------------------------------------------------------------------------
/src/kagglesdk/kaggle_env.py:
--------------------------------------------------------------------------------
 1 | import os
 2 | from enum import Enum
 3 | 
 4 | 
 5 | class KaggleEnv(Enum):
 6 |     LOCAL = 0  # localhost
 7 |     STAGING = 1  # staging.kaggle.com
 8 |     ADMIN = 2  # admin.kaggle.com
 9 |     QA = 3  # qa.kaggle.com
10 |     # Direct prod access is not allowed to have IAP protection during testing, but we support basic auth.
11 |     PROD = 4  # www.kaggle.com
12 | 
13 | 
14 | _env_to_endpoint = {
15 |     KaggleEnv.LOCAL: 'http://localhost',
16 |     KaggleEnv.STAGING: 'https://staging.kaggle.com',
17 |     KaggleEnv.ADMIN: 'https://admin.kaggle.com',
18 |     KaggleEnv.QA: 'https://qa.kaggle.com',
19 |     # See the comment above in KaggleEnv enum.
20 |     KaggleEnv.PROD: 'https://www.kaggle.com',
21 | }
22 | 
23 | 
24 | def get_endpoint(env: KaggleEnv):
25 |     return _env_to_endpoint[env]
26 | 
27 | 
28 | def get_env():
29 |     env = os.getenv('KAGGLE_API_ENVIRONMENT')
30 |     if env is None or env == 'PROD':
31 |         return KaggleEnv.PROD
32 |     if env == 'LOCALHOST':
33 |         return KaggleEnv.LOCAL
34 |     if env == 'ADMIN':
35 |         return KaggleEnv.ADMIN
36 |     if env == 'STAGING':
37 |         return KaggleEnv.STAGING
38 |     if env == 'QA':
39 |         return KaggleEnv.QA
40 |     raise Exception(f'Unrecognized value in KAGGLE_API_ENVIRONMENT: "{env}"')
41 | 


--------------------------------------------------------------------------------
/src/kagglesdk/kernels/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/kernels/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/kernels/services/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/kernels/services/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/kernels/services/kernels_api_service.py:
--------------------------------------------------------------------------------
  1 | from kagglesdk.common.types.file_download import FileDownload
  2 | from kagglesdk.common.types.http_redirect import HttpRedirect
  3 | from kagglesdk.kaggle_http_client import KaggleHttpClient
  4 | from kagglesdk.kernels.types.kernels_api_service import (
  5 |     ApiDownloadKernelOutputRequest,
  6 |     ApiDownloadKernelOutputZipRequest,
  7 |     ApiGetKernelRequest,
  8 |     ApiGetKernelResponse,
  9 |     ApiGetKernelSessionStatusRequest,
 10 |     ApiGetKernelSessionStatusResponse,
 11 |     ApiListKernelFilesRequest,
 12 |     ApiListKernelFilesResponse,
 13 |     ApiListKernelSessionOutputRequest,
 14 |     ApiListKernelSessionOutputResponse,
 15 |     ApiListKernelsRequest,
 16 |     ApiListKernelsResponse,
 17 |     ApiSaveKernelRequest,
 18 |     ApiSaveKernelResponse,
 19 | )
 20 | 
 21 | 
 22 | class KernelsApiClient(object):
 23 | 
 24 |     def __init__(self, client: KaggleHttpClient):
 25 |         self._client = client
 26 | 
 27 |     def list_kernels(self, request: ApiListKernelsRequest = None) -> ApiListKernelsResponse:
 28 |         r"""
 29 |         Args:
 30 |           request (ApiListKernelsRequest):
 31 |             The request object; initialized to empty instance if not specified.
 32 |         """
 33 | 
 34 |         if request is None:
 35 |             request = ApiListKernelsRequest()
 36 | 
 37 |         return self._client.call("kernels.KernelsApiService", "ApiListKernels", request, ApiListKernelsResponse)
 38 | 
 39 |     def list_kernel_files(self, request: ApiListKernelFilesRequest = None) -> ApiListKernelFilesResponse:
 40 |         r"""
 41 |         Args:
 42 |           request (ApiListKernelFilesRequest):
 43 |             The request object; initialized to empty instance if not specified.
 44 |         """
 45 | 
 46 |         if request is None:
 47 |             request = ApiListKernelFilesRequest()
 48 | 
 49 |         return self._client.call("kernels.KernelsApiService", "ApiListKernelFiles", request, ApiListKernelFilesResponse)
 50 | 
 51 |     def get_kernel(self, request: ApiGetKernelRequest = None) -> ApiGetKernelResponse:
 52 |         r"""
 53 |         Args:
 54 |           request (ApiGetKernelRequest):
 55 |             The request object; initialized to empty instance if not specified.
 56 |         """
 57 | 
 58 |         if request is None:
 59 |             request = ApiGetKernelRequest()
 60 | 
 61 |         return self._client.call("kernels.KernelsApiService", "ApiGetKernel", request, ApiGetKernelResponse)
 62 | 
 63 |     def save_kernel(self, request: ApiSaveKernelRequest = None) -> ApiSaveKernelResponse:
 64 |         r"""
 65 |         Args:
 66 |           request (ApiSaveKernelRequest):
 67 |             The request object; initialized to empty instance if not specified.
 68 |         """
 69 | 
 70 |         if request is None:
 71 |             request = ApiSaveKernelRequest()
 72 | 
 73 |         return self._client.call("kernels.KernelsApiService", "ApiSaveKernel", request, ApiSaveKernelResponse)
 74 | 
 75 |     def list_kernel_session_output(
 76 |         self, request: ApiListKernelSessionOutputRequest = None
 77 |     ) -> ApiListKernelSessionOutputResponse:
 78 |         r"""
 79 |         Args:
 80 |           request (ApiListKernelSessionOutputRequest):
 81 |             The request object; initialized to empty instance if not specified.
 82 |         """
 83 | 
 84 |         if request is None:
 85 |             request = ApiListKernelSessionOutputRequest()
 86 | 
 87 |         return self._client.call(
 88 |             "kernels.KernelsApiService", "ApiListKernelSessionOutput", request, ApiListKernelSessionOutputResponse
 89 |         )
 90 | 
 91 |     def get_kernel_session_status(
 92 |         self, request: ApiGetKernelSessionStatusRequest = None
 93 |     ) -> ApiGetKernelSessionStatusResponse:
 94 |         r"""
 95 |         Args:
 96 |           request (ApiGetKernelSessionStatusRequest):
 97 |             The request object; initialized to empty instance if not specified.
 98 |         """
 99 | 
100 |         if request is None:
101 |             request = ApiGetKernelSessionStatusRequest()
102 | 
103 |         return self._client.call(
104 |             "kernels.KernelsApiService", "ApiGetKernelSessionStatus", request, ApiGetKernelSessionStatusResponse
105 |         )
106 | 
107 |     def download_kernel_output(self, request: ApiDownloadKernelOutputRequest = None) -> HttpRedirect:
108 |         r"""
109 |         Meant for use by Kaggle Hub (http bindings and terminology align with that)
110 | 
111 |         Args:
112 |           request (ApiDownloadKernelOutputRequest):
113 |             The request object; initialized to empty instance if not specified.
114 |         """
115 | 
116 |         if request is None:
117 |             request = ApiDownloadKernelOutputRequest()
118 | 
119 |         return self._client.call("kernels.KernelsApiService", "ApiDownloadKernelOutput", request, HttpRedirect)
120 | 
121 |     def download_kernel_output_zip(self, request: ApiDownloadKernelOutputZipRequest = None) -> FileDownload:
122 |         r"""
123 |         Meant for use by Kaggle Hub (and DownloadKernelOutput above)
124 | 
125 |         Args:
126 |           request (ApiDownloadKernelOutputZipRequest):
127 |             The request object; initialized to empty instance if not specified.
128 |         """
129 | 
130 |         if request is None:
131 |             request = ApiDownloadKernelOutputZipRequest()
132 | 
133 |         return self._client.call("kernels.KernelsApiService", "ApiDownloadKernelOutputZip", request, FileDownload)
134 | 


--------------------------------------------------------------------------------
/src/kagglesdk/kernels/types/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/kernels/types/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/kernels/types/kernels_enums.py:
--------------------------------------------------------------------------------
 1 | import enum
 2 | 
 3 | 
 4 | class KernelsListSortType(enum.Enum):
 5 |     HOTNESS = 0
 6 |     COMMENT_COUNT = 1
 7 |     DATE_CREATED = 2
 8 |     DATE_RUN = 3
 9 |     RELEVANCE = 4
10 |     SCORE_ASCENDING = 5
11 |     SCORE_DESCENDING = 6
12 |     VIEW_COUNT = 7
13 |     VOTE_COUNT = 8
14 | 
15 | 
16 | class KernelsListViewType(enum.Enum):
17 |     KERNELS_LIST_VIEW_TYPE_UNSPECIFIED = 0
18 |     PROFILE = 1
19 |     UPVOTED = 2
20 |     EVERYONE = 3
21 |     COLLABORATION = 4
22 |     FORK = 5
23 |     BOOKMARKED = 6
24 |     RECENTLY_VIEWED = 7
25 |     PUBLIC_AND_USERS_PRIVATE = 8
26 | 
27 | 
28 | class KernelWorkerStatus(enum.Enum):
29 |     QUEUED = 0
30 |     RUNNING = 1
31 |     COMPLETE = 2
32 |     ERROR = 3
33 |     CANCEL_REQUESTED = 4
34 |     CANCEL_ACKNOWLEDGED = 5
35 |     NEW_SCRIPT = 6
36 | 


--------------------------------------------------------------------------------
/src/kagglesdk/models/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/models/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/models/services/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/models/services/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/models/services/model_service.py:
--------------------------------------------------------------------------------
 1 | from kagglesdk.kaggle_http_client import KaggleHttpClient
 2 | from kagglesdk.models.types.model_service import GetModelMetricsRequest, GetModelMetricsResponse
 3 | 
 4 | 
 5 | class ModelClient(object):
 6 | 
 7 |     def __init__(self, client: KaggleHttpClient):
 8 |         self._client = client
 9 | 
10 |     def get_model_metrics(self, request: GetModelMetricsRequest = None) -> GetModelMetricsResponse:
11 |         r"""
12 |         Args:
13 |           request (GetModelMetricsRequest):
14 |             The request object; initialized to empty instance if not specified.
15 |         """
16 | 
17 |         if request is None:
18 |             request = GetModelMetricsRequest()
19 | 
20 |         return self._client.call("models.ModelService", "GetModelMetrics", request, GetModelMetricsResponse)
21 | 


--------------------------------------------------------------------------------
/src/kagglesdk/models/types/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/models/types/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/models/types/model_enums.py:
--------------------------------------------------------------------------------
 1 | import enum
 2 | 
 3 | 
 4 | class GatingAgreementRequestsReviewStatus(enum.Enum):
 5 |     GATING_AGREEMENT_REQUESTS_REVIEW_STATUS_UNSPECIFIED = 0
 6 |     GATING_AGREEMENT_REQUESTS_REVIEW_STATUS_PENDING = 1
 7 |     GATING_AGREEMENT_REQUESTS_REVIEW_STATUS_ACCEPTED = 2
 8 |     GATING_AGREEMENT_REQUESTS_REVIEW_STATUS_REJECTED = 3
 9 | 
10 | 
11 | class ListModelsOrderBy(enum.Enum):
12 |     LIST_MODELS_ORDER_BY_UNSPECIFIED = 0
13 |     LIST_MODELS_ORDER_BY_HOTNESS = 1
14 |     LIST_MODELS_ORDER_BY_DOWNLOAD_COUNT = 2
15 |     LIST_MODELS_ORDER_BY_VOTE_COUNT = 3
16 |     LIST_MODELS_ORDER_BY_NOTEBOOK_COUNT = 4
17 |     LIST_MODELS_ORDER_BY_PUBLISH_TIME = 5
18 |     LIST_MODELS_ORDER_BY_CREATE_TIME = 6
19 |     LIST_MODELS_ORDER_BY_UPDATE_TIME = 7
20 |     LIST_MODELS_ORDER_BY_VIEW_TIME_DESC = 8
21 | 
22 | 
23 | class ModelFramework(enum.Enum):
24 |     MODEL_FRAMEWORK_UNSPECIFIED = 0
25 |     MODEL_FRAMEWORK_TENSOR_FLOW_1 = 1
26 |     MODEL_FRAMEWORK_TENSOR_FLOW_2 = 2
27 |     MODEL_FRAMEWORK_TF_LITE = 3
28 |     MODEL_FRAMEWORK_TF_JS = 4
29 |     MODEL_FRAMEWORK_PY_TORCH = 5
30 |     MODEL_FRAMEWORK_JAX = 6
31 |     MODEL_FRAMEWORK_FLAX = 14
32 |     MODEL_FRAMEWORK_PAX = 15
33 |     MODEL_FRAMEWORK_MAX_TEXT = 17
34 |     MODEL_FRAMEWORK_GEMMA_CPP = 18
35 |     MODEL_FRAMEWORK_GGML = 19
36 |     MODEL_FRAMEWORK_GGUF = 21
37 |     MODEL_FRAMEWORK_CORAL = 7
38 |     MODEL_FRAMEWORK_SCIKIT_LEARN = 8
39 |     MODEL_FRAMEWORK_MXNET = 9
40 |     MODEL_FRAMEWORK_ONNX = 10
41 |     MODEL_FRAMEWORK_KERAS = 11
42 |     MODEL_FRAMEWORK_TRANSFORMERS = 16
43 |     MODEL_FRAMEWORK_API = 12
44 |     MODEL_FRAMEWORK_OTHER = 13
45 |     MODEL_FRAMEWORK_TENSOR_RT_LLM = 20
46 |     MODEL_FRAMEWORK_TRITON = 22
47 | 
48 | 
49 | class ModelInstanceType(enum.Enum):
50 |     MODEL_INSTANCE_TYPE_UNSPECIFIED = 0
51 |     MODEL_INSTANCE_TYPE_BASE_MODEL = 1
52 |     MODEL_INSTANCE_TYPE_KAGGLE_VARIANT = 2
53 |     MODEL_INSTANCE_TYPE_EXTERNAL_VARIANT = 3
54 | 
55 | 
56 | class ModelVersionLinkType(enum.Enum):
57 |     MODEL_VERSION_LINK_TYPE_UNSPECIFIED = 0
58 |     MODEL_VERSION_LINK_TYPE_VERTEX_OPEN = 1
59 |     MODEL_VERSION_LINK_TYPE_VERTEX_DEPLOY = 2
60 | 
61 | 
62 | class GatingAgreementRequestsExpiryStatus(enum.Enum):
63 |     GATING_AGREEMENT_REQUESTS_EXPIRY_STATUS_UNSPECIFIED = 0
64 |     GATING_AGREEMENT_REQUESTS_EXPIRY_STATUS_NOT_EXPIRED = 1
65 |     GATING_AGREEMENT_REQUESTS_EXPIRY_STATUS_IS_EXPIRED = 2
66 | 


--------------------------------------------------------------------------------
/src/kagglesdk/security/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/security/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/security/services/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/security/services/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/security/services/oauth_service.py:
--------------------------------------------------------------------------------
 1 | from kagglesdk.common.types.http_redirect import HttpRedirect
 2 | from kagglesdk.kaggle_http_client import KaggleHttpClient
 3 | from kagglesdk.security.types.oauth_service import (
 4 |     ExchangeOAuthTokenRequest,
 5 |     ExchangeOAuthTokenResponse,
 6 |     StartOAuthFlowRequest,
 7 | )
 8 | 
 9 | 
10 | class OAuthClient(object):
11 | 
12 |     def __init__(self, client: KaggleHttpClient):
13 |         self._client = client
14 | 
15 |     def start_oauth_flow(self, request: StartOAuthFlowRequest = None) -> HttpRedirect:
16 |         r"""
17 |         Args:
18 |           request (StartOAuthFlowRequest):
19 |             The request object; initialized to empty instance if not specified.
20 |         """
21 | 
22 |         if request is None:
23 |             request = StartOAuthFlowRequest()
24 | 
25 |         return self._client.call("security.OAuthService", "StartOAuthFlow", request, HttpRedirect)
26 | 
27 |     def exchange_oauth_token(self, request: ExchangeOAuthTokenRequest = None) -> ExchangeOAuthTokenResponse:
28 |         r"""
29 |         Args:
30 |           request (ExchangeOAuthTokenRequest):
31 |             The request object; initialized to empty instance if not specified.
32 |         """
33 | 
34 |         if request is None:
35 |             request = ExchangeOAuthTokenRequest()
36 | 
37 |         return self._client.call("security.OAuthService", "ExchangeOAuthToken", request, ExchangeOAuthTokenResponse)
38 | 


--------------------------------------------------------------------------------
/src/kagglesdk/security/types/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/security/types/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/security/types/authentication.py:
--------------------------------------------------------------------------------
  1 | from kagglesdk.kaggle_object import *
  2 | from typing import Optional, List
  3 | 
  4 | 
  5 | class AuthorizationScope(KaggleObject):
  6 |     r"""
  7 |     Attributes:
  8 |       resource_id (int)
  9 |       permission (AuthorizationPermissionScope)
 10 |       role (AuthorizationRoleScope)
 11 |     """
 12 | 
 13 |     def __init__(self):
 14 |         self._resource_id = 0
 15 |         self._permission = None
 16 |         self._role = None
 17 |         self._freeze()
 18 | 
 19 |     @property
 20 |     def resource_id(self) -> int:
 21 |         return self._resource_id
 22 | 
 23 |     @resource_id.setter
 24 |     def resource_id(self, resource_id: int):
 25 |         if resource_id is None:
 26 |             del self.resource_id
 27 |             return
 28 |         if not isinstance(resource_id, int):
 29 |             raise TypeError('resource_id must be of type int')
 30 |         self._resource_id = resource_id
 31 | 
 32 |     @property
 33 |     def permission(self) -> Optional['AuthorizationPermissionScope']:
 34 |         return self._permission or None
 35 | 
 36 |     @permission.setter
 37 |     def permission(self, permission: Optional['AuthorizationPermissionScope']):
 38 |         if permission is None:
 39 |             del self.permission
 40 |             return
 41 |         if not isinstance(permission, AuthorizationPermissionScope):
 42 |             raise TypeError('permission must be of type AuthorizationPermissionScope')
 43 |         del self.role
 44 |         self._permission = permission
 45 | 
 46 |     @property
 47 |     def role(self) -> Optional['AuthorizationRoleScope']:
 48 |         return self._role or None
 49 | 
 50 |     @role.setter
 51 |     def role(self, role: Optional['AuthorizationRoleScope']):
 52 |         if role is None:
 53 |             del self.role
 54 |             return
 55 |         if not isinstance(role, AuthorizationRoleScope):
 56 |             raise TypeError('role must be of type AuthorizationRoleScope')
 57 |         del self.permission
 58 |         self._role = role
 59 | 
 60 | 
 61 | class AuthorizationPermissionScope(KaggleObject):
 62 |     r"""
 63 |     Attributes:
 64 |       name (str)
 65 |       description (str)
 66 |     """
 67 | 
 68 |     def __init__(self):
 69 |         self._name = ""
 70 |         self._description = None
 71 |         self._freeze()
 72 | 
 73 |     @property
 74 |     def name(self) -> str:
 75 |         return self._name
 76 | 
 77 |     @name.setter
 78 |     def name(self, name: str):
 79 |         if name is None:
 80 |             del self.name
 81 |             return
 82 |         if not isinstance(name, str):
 83 |             raise TypeError('name must be of type str')
 84 |         self._name = name
 85 | 
 86 |     @property
 87 |     def description(self) -> str:
 88 |         return self._description or ""
 89 | 
 90 |     @description.setter
 91 |     def description(self, description: str):
 92 |         if description is None:
 93 |             del self.description
 94 |             return
 95 |         if not isinstance(description, str):
 96 |             raise TypeError('description must be of type str')
 97 |         self._description = description
 98 | 
 99 | 
100 | class AuthorizationRoleScope(KaggleObject):
101 |     r"""
102 |     Attributes:
103 |       name (str)
104 |       description (str)
105 |       permissions (AuthorizationPermissionScope)
106 |     """
107 | 
108 |     def __init__(self):
109 |         self._name = ""
110 |         self._description = None
111 |         self._permissions = []
112 |         self._freeze()
113 | 
114 |     @property
115 |     def name(self) -> str:
116 |         return self._name
117 | 
118 |     @name.setter
119 |     def name(self, name: str):
120 |         if name is None:
121 |             del self.name
122 |             return
123 |         if not isinstance(name, str):
124 |             raise TypeError('name must be of type str')
125 |         self._name = name
126 | 
127 |     @property
128 |     def description(self) -> str:
129 |         return self._description or ""
130 | 
131 |     @description.setter
132 |     def description(self, description: str):
133 |         if description is None:
134 |             del self.description
135 |             return
136 |         if not isinstance(description, str):
137 |             raise TypeError('description must be of type str')
138 |         self._description = description
139 | 
140 |     @property
141 |     def permissions(self) -> Optional[List[Optional['AuthorizationPermissionScope']]]:
142 |         return self._permissions
143 | 
144 |     @permissions.setter
145 |     def permissions(self, permissions: Optional[List[Optional['AuthorizationPermissionScope']]]):
146 |         if permissions is None:
147 |             del self.permissions
148 |             return
149 |         if not isinstance(permissions, list):
150 |             raise TypeError('permissions must be of type list')
151 |         if not all([isinstance(t, AuthorizationPermissionScope) for t in permissions]):
152 |             raise TypeError('permissions must contain only items of type AuthorizationPermissionScope')
153 |         self._permissions = permissions
154 | 
155 | 
156 | AuthorizationScope._fields = [
157 |     FieldMetadata("resourceId", "resource_id", "_resource_id", int, 0, PredefinedSerializer()),
158 |     FieldMetadata(
159 |         "permission",
160 |         "permission",
161 |         "_permission",
162 |         AuthorizationPermissionScope,
163 |         None,
164 |         KaggleObjectSerializer(),
165 |         optional=True,
166 |     ),
167 |     FieldMetadata("role", "role", "_role", AuthorizationRoleScope, None, KaggleObjectSerializer(), optional=True),
168 | ]
169 | 
170 | AuthorizationPermissionScope._fields = [
171 |     FieldMetadata("name", "name", "_name", str, "", PredefinedSerializer()),
172 |     FieldMetadata("description", "description", "_description", str, None, PredefinedSerializer(), optional=True),
173 | ]
174 | 
175 | AuthorizationRoleScope._fields = [
176 |     FieldMetadata("name", "name", "_name", str, "", PredefinedSerializer()),
177 |     FieldMetadata("description", "description", "_description", str, None, PredefinedSerializer(), optional=True),
178 |     FieldMetadata(
179 |         "permissions",
180 |         "permissions",
181 |         "_permissions",
182 |         AuthorizationPermissionScope,
183 |         [],
184 |         ListSerializer(KaggleObjectSerializer()),
185 |     ),
186 | ]
187 | 


--------------------------------------------------------------------------------
/src/kagglesdk/test/test_client.py:
--------------------------------------------------------------------------------
 1 | from kagglesdk import kaggle_env
 2 | from kagglesdk import KaggleClient, KaggleEnv
 3 | 
 4 | # python -m unittest tests.test_authenticate
 5 | 
 6 | import os
 7 | import unittest
 8 | 
 9 | 
10 | class TestClient(unittest.TestCase):
11 | 
12 |     def setUp(self):
13 |         print('setup             class:%s' % self)
14 | 
15 |     def tearDown(self):
16 |         print('teardown          class:TestStuff')
17 | 
18 |     # Environment
19 | 
20 |     def test_kaggle_environment(self):
21 |         os.environ['KAGGLE_API_ENVIRONMENT'] = 'PROD'
22 | 
23 |         env = kaggle_env.get_env()
24 |         self.assertEqual(env, KaggleEnv.PROD)
25 | 
26 |         endpoint = kaggle_env.get_endpoint(env)
27 |         self.assertEqual(endpoint, 'https://www.kaggle.com')
28 | 
29 |     # Client
30 | 
31 |     def test_kaggle_client(self):
32 |         client = KaggleClient(env=KaggleEnv.PROD, verbose=False, username='dinosaur', password='xxxxxxxxxxxx')
33 | 
34 |         self.assertEqual(client.username, 'dinosaur')
35 |         self.assertEqual(client.password, 'xxxxxxxxxxxx')
36 |         self.assertEqual(client.http_client()._endpoint, 'https://www.kaggle.com')
37 |         self.assertEqual(client.http_client()._verbose, False)
38 | 
39 | 
40 | if __name__ == '__main__':
41 |     unittest.main()
42 | 


--------------------------------------------------------------------------------
/src/kagglesdk/users/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/users/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/users/services/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/users/services/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/users/services/account_service.py:
--------------------------------------------------------------------------------
 1 | from kagglesdk.kaggle_http_client import KaggleHttpClient
 2 | from kagglesdk.users.types.account_service import GenerateAccessTokenRequest, GenerateAccessTokenResponse
 3 | 
 4 | 
 5 | class AccountClient(object):
 6 | 
 7 |     def __init__(self, client: KaggleHttpClient):
 8 |         self._client = client
 9 | 
10 |     def generate_access_token(self, request: GenerateAccessTokenRequest = None) -> GenerateAccessTokenResponse:
11 |         r"""
12 |         Args:
13 |           request (GenerateAccessTokenRequest):
14 |             The request object; initialized to empty instance if not specified.
15 |         """
16 | 
17 |         if request is None:
18 |             request = GenerateAccessTokenRequest()
19 | 
20 |         return self._client.call("users.AccountService", "GenerateAccessToken", request, GenerateAccessTokenResponse)
21 | 


--------------------------------------------------------------------------------
/src/kagglesdk/users/types/__init__.py:
--------------------------------------------------------------------------------
https://raw.githubusercontent.com/Kaggle/kaggle-api/c27de26856994c7919144901f0636540596a022d/src/kagglesdk/users/types/__init__.py


--------------------------------------------------------------------------------
/src/kagglesdk/users/types/users_enums.py:
--------------------------------------------------------------------------------
 1 | import enum
 2 | 
 3 | 
 4 | class UserAchievementTier(enum.Enum):
 5 |     NOVICE = 0
 6 |     CONTRIBUTOR = 1
 7 |     EXPERT = 2
 8 |     MASTER = 3
 9 |     GRANDMASTER = 4
10 |     STAFF = 5
11 |     """Kaggle admins"""
12 |     ORGANIZATION = 11
13 |     """Organizations"""
14 |     RECALC = 21
15 |     """Flag user for tier recalculation"""
16 | 
17 | 
18 | class CollaboratorType(enum.Enum):
19 |     COLLABORATOR_TYPE_UNSPECIFIED = 0
20 |     READER = 1
21 |     WRITER = 2
22 |     OWNER = 3
23 |     ADMIN = 4
24 | 


--------------------------------------------------------------------------------
/src/setup.cfg:
--------------------------------------------------------------------------------
1 | [metadata]
2 | description-file = README.md


--------------------------------------------------------------------------------
/src/setup.py:
--------------------------------------------------------------------------------
 1 | # coding=utf-8
 2 | from setuptools import setup, find_packages
 3 | 
 4 | # Note: pyproject.toml seems to be chosen by pip install over setup.py, so this
 5 | # file should not be used anymore. However, cloudbuild.yaml still uses setup.py
 6 | # to drive the build that is published to pypi.org. That needs to be changed
 7 | # before this file can be removed. And, due to that, pyproject.toml needs to be
 8 | # deleted before a release can be made.
 9 | # https://packaging.python.org/en/latest/guides/modernize-setup-py-project/
10 | setup(
11 |     name='kaggle',
12 |     version='1.7.4.2',
13 |     description='Kaggle API',
14 |     long_description=(
15 |         'Official API for https://www.kaggle.com, accessible using a command line '
16 |         'tool implemented in Python. Beta release - Kaggle reserves the right to '
17 |         'modify the API functionality currently offered.'
18 |     ),
19 |     author='Kaggle',
20 |     author_email='support@kaggle.com',
21 |     url='https://github.com/Kaggle/kaggle-api',
22 |     project_urls={
23 |         'Documentation': 'https://www.kaggle.com/docs/api',
24 |         'GitHub': 'https://github.com/Kaggle/kaggle-api',
25 |         'Tracker': 'https://github.com/Kaggle/kaggle-api/issues',
26 |     },
27 |     keywords=['Kaggle', 'API'],
28 |     entry_points={'console_scripts': ['kaggle = kaggle.cli:main']},
29 |     install_requires=[
30 |         'six >= 1.10',
31 |         'certifi >= 2023.7.22',
32 |         'python-dateutil',
33 |         'requests',
34 |         'tqdm',
35 |         'python-slugify',
36 |         'urllib3',
37 |         'bleach',
38 |         'protobuf',
39 |         'hatchling >= 1.27.0',
40 |     ],
41 |     packages=find_packages(
42 |         where='src',
43 |         include=['kaggle*'],
44 |     ),
45 |     package_dir={"": "src"},
46 | )
47 | 


--------------------------------------------------------------------------------
/tests/dataset/data.csv:
--------------------------------------------------------------------------------
1 | id, fruit
2 | 1, apple
3 | 2, banana
4 | 3, citrus
5 | 4, apple
6 | 5, durian


--------------------------------------------------------------------------------
/tests/kernel/testing.ipynb:
--------------------------------------------------------------------------------
1 | {"metadata":{"kernelspec":{"language":"python","display_name":"Python 3","name":"python3"},"language_info":{"name":"python","version":"3.10.13","mimetype":"text/x-python","codemirror_mode":{"name":"ipython","version":3},"pygments_lexer":"ipython3","nbconvert_exporter":"python","file_extension":".py"},"kaggle":{"accelerator":"none","dataSources":[],"dockerImageVersionId":30646,"isInternetEnabled":true,"language":"python","sourceType":"notebook","isGpuEnabled":false}},"nbformat_minor":4,"nbformat":4,"cells":[{"cell_type":"code","source":"# This Python 3 environment comes with many helpful analytics libraries installed\n# It is defined by the kaggle/python Docker image: https://github.com/kaggle/docker-python\n# For example, here's several helpful packages to load\n\nimport numpy as np # linear algebra\nimport pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)\n\n# Input data files are available in the read-only \"../input/\" directory\n# For example, running this (by clicking run or pressing Shift+Enter) will list all files under the input directory\n\nimport os\nfor dirname, _, filenames in os.walk('/kaggle/input'):\n    for filename in filenames:\n        print(os.path.join(dirname, filename))\n\n# You can write up to 20GB to the current directory (/kaggle/working/) that gets preserved as output when you create a version using \"Save & Run All\" \n# You can also write temporary files to /kaggle/temp/, but they won't be saved outside of the current session","metadata":{"_uuid":"8f2839f25d086af736a60e9eeb907d3b93b6e0e5","_cell_guid":"b1076dfc-b9ad-4769-8c92-a6c4dae69d19","execution":{"iopub.status.busy":"2024-06-11T17:18:41.771461Z","iopub.execute_input":"2024-06-11T17:18:41.771892Z","iopub.status.idle":"2024-06-11T17:18:43.04124Z","shell.execute_reply.started":"2024-06-11T17:18:41.771858Z","shell.execute_reply":"2024-06-11T17:18:43.03999Z"},"trusted":true},"execution_count":null,"outputs":[]}]}


--------------------------------------------------------------------------------
/tests/model/instance/data.csv:
--------------------------------------------------------------------------------
1 | id, fruit
2 | 1, apple
3 | 2, banana
4 | 3, citrus
5 | 4, apple
6 | 5, durian


--------------------------------------------------------------------------------
/tests/model/instance/version/metadata.json:
--------------------------------------------------------------------------------
1 | {}


--------------------------------------------------------------------------------
/tools/GeneratePythonLibrary.sh:
--------------------------------------------------------------------------------
  1 | #!/usr/bin/env bash
  2 | 
  3 | set -e
  4 | 
  5 | readonly LOCAL_ENV="local"
  6 | readonly PROD_ENV="prod"
  7 | 
  8 | function usage {
  9 |   echo "Usage  : $1 [--install|--editable] [--test local|prod]"
 10 |   echo
 11 |   echo "         --install (-i): Install the package locally."
 12 |   echo "         --editable (-e): Make the installed package always reference your latest"
 13 |   echo "                          source code. Implies \"-i|--install\". Be aware that changes to the \"src\""
 14 |   echo "                          directory won't be reflected. See the README for details."
 15 |   echo "         --test (-t) [$LOCAL_ENV|$PROD_ENV]: Run tests (unit_tests.py) against http://localhost" 
 16 |   echo "                                   or https://www.kaggle.com."
 17 |   echo "         --watch (-w): Run the script in watch mode. It will watch the files under the \"template\""
 18 |   echo "                       directory and KaggleSwagger* files, and regenerate the package when there is a change."
 19 |   echo ""
 20 | }
 21 | 
 22 | INSTALL="no"
 23 | INSTALL_EDITABLE="no"
 24 | TEST=""
 25 | WATCH="no"
 26 | 
 27 | while [[ $# -gt 0 ]]; do
 28 |   arg="$1"
 29 |   case $arg in
 30 |     --install|-i)
 31 |       INSTALL="yes"
 32 |       ;;
 33 |     --editable|-e|--editable-install|--install-editable)
 34 |       INSTALL_EDITABLE="yes"
 35 |       ;;
 36 |     --test|-t)
 37 |       TEST=$2
 38 |       if [[ "$TEST" != "$LOCAL_ENV" ]] && [[ "$TEST" != "$PROD_ENV" ]]; then
 39 |         echo -e "Invalid value for arg \"$1\": \"$TEST\". Must be \"$LOCAL_ENV\" or \"$PROD_ENV\".\n"
 40 |         usage $0
 41 |         exit 0
 42 |       fi
 43 |       shift
 44 |       ;;
 45 |     --watch|-w)
 46 |       WATCH="yes"
 47 |       INSTALL_EDITABLE="yes"
 48 |       ;;
 49 |     --help|-h)
 50 |       usage $0
 51 |       exit 0
 52 |       ;;
 53 |     *)
 54 |       echo -e "Invalid argument: \"$1\".\n"
 55 |       usage $0
 56 |       exit 1
 57 |       ;;
 58 |   esac
 59 |   shift  # Proceed with the next argument.
 60 | done
 61 | 
 62 | SELF_DIR=$(dirname $(realpath $0))
 63 | SELF_DIR=${SELF_DIR%/*} # remove the last directory (tools) from the path
 64 | cd $SELF_DIR
 65 | 
 66 | KAGGLE_XDG_CONFIG_DIR="${XDG_CONFIG_HOME:-$HOME/.config}/kaggle"
 67 | mkdir -p "$KAGGLE_XDG_CONFIG_DIR"
 68 | KAGGLE_DEV_CONFIG_DIR=$(realpath "$KAGGLE_XDG_CONFIG_DIR/dev")
 69 | 
 70 | trap cleanup EXIT
 71 | 
 72 | function init {
 73 |   cd $SELF_DIR
 74 | 
 75 |   mkdir -p "$KAGGLE_XDG_CONFIG_DIR" && chmod 700 "$KAGGLE_XDG_CONFIG_DIR"
 76 | 
 77 |   echo "rm -rf kaggle kagglesdk"
 78 |   rm -rf kaggle kagglesdk
 79 | 
 80 |   create-local-creds
 81 | }
 82 | 
 83 | function reset {
 84 |   cd $SELF_DIR
 85 | 
 86 |   echo "run formatter"
 87 |   if [ -x "$(command -v black)" ]; then
 88 |     black .
 89 |   else
 90 |     echo "black is not installed on your system"
 91 |   fi
 92 | }
 93 | 
 94 | function create-local-creds {
 95 |   # Generate a separate dev credentials file (kaggle.json) to use when running against
 96 |   # http://localhost. This token only works when the webtier is running locally in debug
 97 |   # mode. When running against localhost, we set KAGGLE_CONFIG_DIR env var to
 98 |   # "~/.config/kaggle/dev/" so that the Python client searches for kaggle.json under this folder
 99 |   # and uses dummy dev creds
100 |   local kaggle_config_file="$KAGGLE_DEV_CONFIG_DIR/kaggle.json"
101 |   mkdir -p $KAGGLE_DEV_CONFIG_DIR
102 |   local username=${KAGGLE_DEVELOPER:-$USER}
103 |   echo "{\"username\":\"$username\",\"key\":\"local_api_token\"}" > $kaggle_config_file
104 |   chmod 600 $kaggle_config_file
105 | }
106 | 
107 | function copy-src {
108 |   cp ./src/setup.py .
109 |   cp ./src/setup.cfg .
110 |   cp -r ./src/kaggle .
111 |   cp -r ./src/kagglesdk .
112 | }
113 | 
114 | function run-tests {
115 |   if ! which kaggle > /dev/null 2> /dev/null; then
116 |     echo "Warning: \"kaggle\" is not in PATH. Please add \"~/.local/bin\" to PATH in ~/.bashrc."
117 |     return 0
118 |   fi
119 | 
120 |   if [[ "$TEST" == "$LOCAL_ENV" ]]; then
121 |     source tools/use-localhost.sh
122 |   elif [[ "$TEST" == "$PROD_ENV" ]]; then
123 |     source tools/use-prod.sh
124 |   else
125 |     return 0 # Nothing to do
126 |   fi
127 | 
128 |   cd tests
129 |   ln -s ../kagglesdk .
130 |   ln -s ../kaggle .
131 |   python3 unit_tests.py
132 |   rm kaggle kagglesdk
133 |   cd ..
134 | }
135 | 
136 | function install-package {
137 |   pip3 install --break-system-packages --require-hashes -r requirements.txt 
138 |   if [[ "$INSTALL_EDITABLE" == "yes" ]];  then
139 |     pip3 install --break-system-packages --upgrade --editable .
140 |   elif [[ "$INSTALL" == "yes" ]];  then
141 |     pip3 install --break-system-packages --upgrade .
142 |   fi
143 | }
144 | 
145 | function cleanup {
146 |   cd $SELF_DIR
147 |   rm -rf tox.ini \
148 |     test-requirements.txt \
149 |     test \
150 |     .travis.yml \
151 |     git_push.sh \
152 |     sample_submission.csv \
153 |     ds_salaries.csv \
154 |     test.csv \
155 |     house-prices-advanced-regression-techniques.zip \
156 |     data-science-salaries-2023.zip \
157 |     kaggle/*.py-e \
158 |     kaggle/api/*.py-e \
159 |     kaggle/*.py.bak
160 | }
161 | 
162 | function run {
163 |   reset
164 | 
165 |   copy-src
166 |   install-package
167 |   run-tests
168 | 
169 |   echo -e "\nGenerated the \"kaggle\" package successfully!"
170 | }
171 | 
172 | WATCHED_EVENTS="-e create -e modify -e delete"
173 | 
174 | function watch-src {
175 |   local watched_paths="$SELF_DIR/src"
176 | 
177 |   echo "Watching for changes under \"src\"..."
178 |   while inotifywait -q -r $WATCHED_EVENTS --format "%e %w%f" $watched_paths; do
179 |     echo "Copying changes..."
180 |     copy-src
181 |     echo "Done!"
182 |     echo -e "\nWatching for changes under \"src\"..."
183 |   done
184 | }
185 | 
186 | function watch {
187 |   # Run once and wait for changes.
188 |   run
189 |   # Disable --editable for the following runs as it is enough to do --editable once and modify under the
190 |   # "src" folder files which will be then copied to the "kaggle" folder by "run" below on file changes.
191 |   INSTALL_EDITABLE="no"
192 |   INSTALL="no"
193 |   TEST="no"
194 | 
195 |   echo
196 |   watch-src
197 |   local pid=$!
198 |   wait $pid
199 | }
200 | 
201 | init
202 | 
203 | if [[ "$WATCH" == "yes" ]]; then
204 |   watch
205 | else
206 |   run
207 | fi
208 | 


--------------------------------------------------------------------------------
/tools/cicd/integration-tests.yaml:
--------------------------------------------------------------------------------
 1 | steps:
 2 |    # Access and store the secret in a file on a shared volume
 3 |   - name: 'gcr.io/cloud-builders/gcloud'
 4 |     id: 'download-secrets'
 5 |     script: |
 6 |       #!/usr/bin/env bash
 7 |       gcloud secrets versions access latest --secret=integration-tests --project=464139560241 > /root/secrets.sh
 8 |     volumes:
 9 |     - name: 'root'
10 |       path: /root
11 | 
12 | 
13 |   # Source the secrets and run integration tests using the built Python image
14 |   - name: us-docker.pkg.dev/$PROJECT_ID/tools/hatch:$_PYTHON_VERSION
15 |     id: integration-tests
16 |     waitFor: ['download-secrets']
17 |     script: |
18 |       #!/usr/bin/env bash
19 |       export KAGGLE_USERNAME
20 |       export KAGGLE_KEY
21 |       source /root/secrets.sh
22 |       hatch run integration-test
23 |     volumes:
24 |     - name: 'root'
25 |       path: /root
26 | 
27 | substitutions:
28 |   _PYTHON_VERSION: '3.11'
29 | 


--------------------------------------------------------------------------------
/tools/releases/Dockerfile:
--------------------------------------------------------------------------------
 1 | FROM debian:12.0
 2 | 
 3 | # Install some useful tools.
 4 | RUN apt-get update -y && \
 5 |     apt-get install -y sudo \
 6 |                        curl \
 7 |                        unzip \
 8 |                        default-jre \
 9 |                        python3-pip
10 | 
11 | COPY requirements.txt requirements.txt
12 | RUN cat requirements.txt
13 | RUN pip install --require-hashes -r requirements.txt --break-system-packages
14 | 
15 | ENTRYPOINT ["/bin/bash"]


--------------------------------------------------------------------------------
/tools/releases/cloudbuild.yaml:
--------------------------------------------------------------------------------
  1 | steps:
  2 |   # Import builder if exists.
  3 |   # Note: the reason to use bash is to be able to return an exit code 0 even if
  4 |   # the docker image doesn't exist yet.
  5 |   - name: "gcr.io/cloud-builders/docker"
  6 |     entrypoint: "bash"
  7 |     args:
  8 |       - "-c"
  9 |       - |
 10 |         docker pull ${_IMAGE_REPO_NAME}/${PROJECT_ID}/cli-releaser || exit 0
 11 | 
 12 |   # Build a modified version of the python image, including tools to build and
 13 |   # release the Kaggle CLI.
 14 |   # Use the previous built image as cache.
 15 |   - name: "gcr.io/cloud-builders/docker"
 16 |     dir: "tools/releases"
 17 |     args:
 18 |       - build
 19 |       - -f
 20 |       - Dockerfile
 21 |       - -t
 22 |       - ${_IMAGE_REPO_NAME}/${PROJECT_ID}/cli-releaser
 23 |       - --cache-from
 24 |       - ${_IMAGE_REPO_NAME}/${PROJECT_ID}/cli-releaser
 25 |       - .
 26 | 
 27 |   - name: "${_IMAGE_REPO_NAME}/${PROJECT_ID}/cli-releaser"
 28 |     id: generate-cli
 29 |     entrypoint: bash
 30 |     args:
 31 |       - "-c"
 32 |       - |
 33 |         mkdir -p ~/.kaggle/dev # Directory expected by following script
 34 |         ./tools/GeneratePythonLibrary.sh
 35 |         python3 -m pip install build --break-system-packages
 36 |         python3 -m build
 37 |         # Move the built CLI to a volume that will survive to next steps.
 38 |         mv dist /root/
 39 |     volumes:
 40 |       - name: "root"
 41 |         path: /root
 42 | 
 43 |   # Get the pypi token from Secret Manager, and create the ~/.pypirc file.
 44 |   - name: "gcr.io/cloud-builders/gcloud"
 45 |     id: create-credentials-pypirc
 46 |     entrypoint: "bash"
 47 |     args:
 48 |       - "-c"
 49 |       - |
 50 |         token_test=$(gcloud secrets versions access latest --secret=test-pypi-token)
 51 |         token=$(gcloud secrets versions access latest --secret=pypi-token)
 52 |         cat >~/.pypirc <<EOL
 53 |         [distutils]
 54 |         index-servers =
 55 |           pypi
 56 |           pypitest
 57 |         [pypi]
 58 |         repository: https://upload.pypi.org/legacy/
 59 |         username=__token__
 60 |         password=${token}
 61 |         [pypitest]
 62 |         repository: https://test.pypi.org/legacy/
 63 |         username=__token__
 64 |         password=${token_test}
 65 |         EOL
 66 |     volumes:
 67 |       - name: "root"
 68 |         path: /root
 69 | 
 70 |   - name: ${_IMAGE_REPO_NAME}/${PROJECT_ID}/cli-releaser
 71 |     id: release-pypitest
 72 |     waitFor: ["generate-cli", "create-credentials-pypirc"]
 73 |     entrypoint: bash
 74 |     args:
 75 |       - "-c"
 76 |       - |
 77 |         if [ "$_TO_TEST" = "false" ] ; then
 78 |             echo "Deployment to pypitest disabled, set substitution _TO_TEST to true if you want otherwise."
 79 |             exit 0
 80 |         fi
 81 |         twine upload /root/dist/* -r pypitest
 82 |     volumes:
 83 |       - name: "root"
 84 |         path: /root
 85 | 
 86 |   - name: ${_IMAGE_REPO_NAME}/${PROJECT_ID}/cli-releaser
 87 |     id: release-pypi
 88 |     waitFor: ["release-pypitest"]
 89 |     entrypoint: bash
 90 |     args:
 91 |       - "-c"
 92 |       - |
 93 |         if [ "$_TO_PROD" = "false" ] ; then
 94 |             echo "Deployment to pypi disabled, set substitution _TO_PROD to true if you want otherwise."
 95 |             exit 0
 96 |         fi
 97 |         twine upload /root/dist/* -r pypi
 98 |     volumes:
 99 |       - name: "root"
100 |         path: /root
101 | 
102 | images: ["${_IMAGE_REPO_NAME}/${PROJECT_ID}/cli-releaser"]
103 | 
104 | substitutions:
105 |   _IMAGE_REPO_NAME: us-docker.pkg.dev/kaggle-cicd/tools
106 |   _TO_TEST: "false"
107 |   _TO_PROD: "false"
108 | 


--------------------------------------------------------------------------------
/tools/releases/requirements.in:
--------------------------------------------------------------------------------
1 | twine==6.0.1
2 | pkginfo==1.12.0


--------------------------------------------------------------------------------
/tools/use-localhost.sh:
--------------------------------------------------------------------------------
 1 | # Source this file to run Kaggle Api V1 against http://localhost.
 2 | 
 3 | if [[ "$0" == "$BASH_SOURCE" ]]; then
 4 |   echo -e "Source this file to run kaggle api cli against localhost:\n"
 5 |   echo "$ source use-localhost.sh"
 6 |   echo
 7 |   exit 1
 8 | fi
 9 | 
10 | export KAGGLE_API_ENDPOINT=http://localhost
11 | export KAGGLE_CONFIG_DIR=$(realpath "${XDG_CONFIG_HOME:-$HOME/.config}/kaggle/dev")
12 | 
13 | KAGGLE_CONFIG_FILE="$KAGGLE_CONFIG_DIR/kaggle.json"
14 | if ! [[ -f "$KAGGLE_CONFIG_FILE" ]]; then
15 |   # Generate a separate dev credentials file (kaggle.json) to use when running against
16 |   # http://localhost. This token only works when the webtier is running locally in debug
17 |   # mode. When running against localhost, we set KAGGLE_CONFIG_DIR env var to
18 |   # "~/.config/kaggle/dev/" so that the Python client searches for kaggle.json under this folder
19 |   # and uses dummy dev creds
20 |   
21 |   mkdir -p $KAGGLE_CONFIG_DIR
22 |   username=${KAGGLE_DEVELOPER:-$USER}
23 |   echo "Creating a dev credentials file (kaggle.json)..."
24 |   echo "{\"username\":\"$username\",\"key\":\"local_api_token\"}" > $KAGGLE_CONFIG_FILE
25 |   chmod 600 $KAGGLE_CONFIG_FILE
26 |   echo "dev credentials created for username '$username'."
27 |   echo "PLEASE VERIFY this matches your Kaggle username!"
28 |   echo "If not, update the $KAGGLE_CONFIG_DIR/kaggle.json file manually to set your Kaggle username. You will only need to do this once."
29 | fi
30 | 


--------------------------------------------------------------------------------
/tools/use-prod.sh:
--------------------------------------------------------------------------------
 1 | # Source this file to run Kaggle Api V1 against https://www.kaggle.com.
 2 | 
 3 | if [[ "$0" == "$BASH_SOURCE" ]]; then
 4 |   echo -e "Source this file to run kaggle api cli against prod:\n"
 5 |   echo "$ source use-prod.sh"
 6 |   echo
 7 |   exit 1
 8 | fi
 9 | 
10 | unset KAGGLE_API_ENDPOINT
11 | unset KAGGLE_CONFIG_DIR
12 | 
13 | if ! [[ -f "${XDG_CONFIG_HOME:-$HOME/.config}/kaggle/kaggle.json" ]]; then
14 |   echo "Warning: Please download an API token at https://www.kaggle.com/settings and"
15 |   echo "copy it to home directory to run the client against prod."
16 |   echo
17 | else
18 |   chmod 600 "${XDG_CONFIG_HOME:-$HOME/.config}/kaggle/kaggle.json"
19 | fi


---------------------------------------------------------