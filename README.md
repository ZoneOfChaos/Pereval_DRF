## Pereval-API

### Описание проекта

API мобильного приложения Федерации Спортивного Туризма России (ФСТР) с помощью Django Rest Framework. 


## Документация для Эндпоинтов 

All URIs are relative to */*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*SubmitDataApi* | [**submit_data_create**](docs/SubmitDataApi.md#submit_data_create) | **POST** /submitData | Добавление перевала
*SubmitDataApi* | [**submit_data_partial_update**](docs/SubmitDataApi.md#submit_data_partial_update) | **PATCH** /submitData/{id}/ |  Редактирование перевала
*SubmitDataApi* | [**submit_data_retrieve**](docs/SubmitDataApi.md#submit_data_retrieve) | **GET** /submitData/{id}/ | Извлечение данных о перевале
*SubmitDataApi* | [**submit_data_user_email_list**](docs/SubmitDataApi.md#submit_data_user_email_list) | **GET** /submitData/user__email&#x3D;{email} | Извлечение списка перевалов пользователя


