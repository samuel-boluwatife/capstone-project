Capstone Project 1 – Deploying a Static Website with AWS
Project Overview

This project demonstrates how to deploy a static website using Amazon S3 for hosting and CloudFront as a content delivery network (CDN). The goal is to make the website publicly accessible, scalable, and fast from any location.

The services used in this project are:

Amazon S3 – to store and host the website files.

Amazon CloudFront – to distribute the website globally with low latency.

Architecture

User Browser → CloudFront CDN → S3 Bucket (Static Website Hosting)

CloudFront caches the website content and serves it quickly to users around the world.
