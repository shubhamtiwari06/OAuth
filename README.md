# OAuth 2.0

## Introduction

OAuth 2.0 is a web based authorization protocol framework.Authorization flow in OAuth 2.0 resembles **Delegated Authorization**.A delegated authorization is when a user authorizes a third-party application to access their account with a limited scope.Let me give you an example to make this easier for you.Suppose you download a email scheduling application now in order to use this application an access to your gmail account is required by this application.Since Gmail is a protecetd web application it cannot trust a third-party application and give it the access. So what do we do then? Well in these kind of situations where an access to an account is required by a third-party application we use OAuth 2.0.This is a very basic idea of what OAuth 2.0 really is and we will be discussing it in great detail but before that lets understand some terminologies associated with OAuth 2.0.

## Terms used in OAuth 2.0

### Resource Owner
A resource owner is the user who owns the resource for which the third party application is asking access to.The application’s access to the user’s account is limited to the “scope” of the authorization granted by the user (e.g. read or write access).

### Resource Server
A proteced web server on which the resources are usually hosted is the resource server. It interacts with the authorization server to verify the identity of the user.

### Authorization Server
Authorization server verifies the Identity of the user and later issues tokens to the applications so that the applications can access the protected resources from the resource srver.

### Third-Party Application
Third-party application is the application that the user is using to access the resource and is not directly trusted by the resource server. 