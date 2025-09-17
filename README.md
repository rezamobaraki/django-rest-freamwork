# Django REST Framework Demo

![Restful](logo.png)

Hello friends! This is a demo project by [Reza Mobaraki](https://www.linkedin.com/in/reza-mobaraki/)

## Table of contents

* [General info](#general-info)
* [Technologies](#technologies)
* [Features](#features)
* [Setup](#setup)
* [Help](#help)
* [Credits](#credits)
* [Contributors](#contributors)
* [License](#license)

## General info

This project demonstrates various features and implementations of Django REST Framework (DRF). It serves as a learning resource and reference implementation for building RESTful APIs with Django.

## Features

This project showcases the following Django REST Framework features:

* **Response** - Custom response handling
* **Serializer** - Data serialization and validation
* **Authentication**:
  - Basic Authentication
  - Session Authentication 
  - Token Authentication
* **ViewSets** - Organized view logic
* **Routers** - URL routing for APIs
* **Validators** - Custom data validation
* **Throttling** - API rate limiting
* **Pagination** - Result pagination
* **Serializer Relations** - Handling related data

## Technologies

Project is created with:

* **Python**: 3.9
* **Django**: 3.2.3
* **Django REST Framework**: 3.12.4

## Setup

Follow these steps to set up the project locally:

### 1. Create virtual environment

```shell
virtualenv -p python3 venv 
```

### 2. Activate virtual environment

```shell
source venv/bin/activate  
```

### 3. Install dependencies

```shell
pip install -r requirements.txt
```

### 4. Run Django server

```shell
python manage.py runserver
```

The application will be available at `http://127.0.0.1:8000/`

## Help

If you are considering a particular method or more modern technology to add to this project, please send a merge request. I will add you to the credits and contributors section.

## Credits

* [mongard](https://www.mongard.ir/courses/drf)

## Contributors

* [rezamobaraki](https://github.com/rezamobaraki)

## License

Distributed under the MIT License. See [license](LICENSE) for more information.