#-------------------------------------------------------------------------------------------------------------
# Copyright (c) Microsoft Corporation. All rights reserved.
# Licensed under the MIT License. See https://go.microsoft.com/fwlink/?linkid=2090316 for license information.
#-------------------------------------------------------------------------------------------------------------

# FROM python:3
FROM jupyter/datascience-notebook:latest

RUN pip install flake8 pytest pandas numpy matplotlib

# Avoid warnings by switching to noninteractive
ENV DEBIAN_FRONTEND=noninteractive