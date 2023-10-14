# Flask Student Face Recognition App Documentation

This documentation provides an overview of the Flask-based student face recognition application.

## Table of Contents

1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Application Structure](#application-structure)
4. [Configuration](#configuration)
5. [Routes](#routes)
    - [Add Student](#add-student)
    - [Detect Faces](#detect-faces)
    - [Recognize Face](#recognize-face)
    - [Video Feed](#video-feed)
    - [Delete Student](#delete-student)
    - [Home](#home)
    - [Students](#students)
    - [Live](#live)
    - [Media](#media)
6. [File Uploads](#file-uploads)
7. [Dependencies](#dependencies)
8. [Running the Application](#running-the-application)

## Introduction

The Flask Student Face Recognition application is a web-based system for managing student records and performing real-time face recognition using webcam input. It allows users to add student information and their photos, which are used for face recognition. The application also provides a live video feed for real-time face detection and recognition.

## Prerequisites

Before running the application, make sure you have the following prerequisites:

- Python 3.x
- Flask
- Flask-SQLAlchemy
- Flask-WTF
- OpenCV (cv2)
- face_recognition

You can install these dependencies using `pip`.

## Application Structure

The application's directory structure is as follows:

