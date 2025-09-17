# Django REST Framework Tutorial

![Django REST Framework](logo.png)

A comprehensive Django REST Framework tutorial project created by [Reza Mobaraki](https://www.linkedin.com/in/reza-mobaraki/)

This project demonstrates various Django REST Framework features and concepts through practical examples and implementations.

## Table of contents

* [General info](#general-info)
* [Technologies](#technologies)
* [Contributing](#contributing)
* [Setup](#setup)
* [Credits](#credits)
* [Contributors](#contributors)
* [License](#license)

## General info

This project is a comprehensive tutorial for Django REST Framework (DRF) that covers essential concepts and practical implementations. It serves as a learning resource for developers who want to master REST API development using Django.

### Features Covered

This tutorial demonstrates the following Django REST Framework features:

* **Response Handling** - Custom response formatting and status codes
* **Serializers** - Data validation and transformation
* **Authentication Methods**:
  - Basic Authentication
  - Session Authentication  
  - Token Authentication
* **ViewSets** - Class-based views for CRUD operations
* **Routers** - Automatic URL routing for ViewSets
* **Validators** - Custom and built-in field validation
* **Throttling** - Rate limiting for API endpoints
* **Pagination** - Efficient data pagination strategies
* **Serializer Relations** - Handling related model data

## Technologies

This project is built with:

* **Python**: 3.9+
* **Django**: 3.2.3
* **Django REST Framework**: 3.12.4

## Contributing

If you have ideas for improvements, modern technologies, or new features that would enhance this tutorial project, please feel free to:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

All contributors will be acknowledged in the credits and contributors section.

## Setup

Follow these steps to set up the project locally:

### 1. Create Virtual Environment

```shell
virtualenv -p python3 venv 
```

### 2. Activate Virtual Environment

```shell
source venv/bin/activate  
```

### 3. Install Dependencies

```shell
pip install -r requirements.txt
```

### 4. Run Database Migrations

```shell
python manage.py migrate
```

### 5. Start Development Server

```shell
python manage.py runserver
```

The application will be available at `http://localhost:8000/`

## Credits

* [mongard](https://www.mongard.ir/courses/drf)

## Contributors

* [rezamobaraki](https://github.com/rezamobaraki)

## License

Distributed under the MIT License. See [license](LICENSE) for more information.