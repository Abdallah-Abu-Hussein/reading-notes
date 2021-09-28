# In your own words, describe what each group of status codes represents:

## 100’s =
These are informational status codes; they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client.
## 200’s =
These are the success codes. They tell the client that its request was accepted. In the case of asynchronous processing of a request (202), this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending.
## 300’s = 
These are redirect codes. They tell the customer that the resource they are requesting is not available at the expected location anymore. This can have multiple reasons, temporary or permanent, but the customer must issue an order to the new location.
## 400’s =
These are client error codes. They are all related to invalid requests sent by the client to the server. There are several reasons for this, timeouts, wrong URI, missing authentication, etc. The client sends an invalid input and must confirm that the input parameters are correct before retrying the request.

## 500’s =

These are server error codes. It often indicates problems with overburdened servers or unreachable servers behind proxy servers, but sometimes it can be directly related to client requests that lead to error exceptions on the server. These errors can be temporary or permanent. Usually, the customer should retry the same request.

## What is status code 202?

The HyperText Transfer Protocol (HTTP) 202 Accepted response status code indicates that the request has been accepted for processing, but the processing has not been completed; in fact, processing may not have started yet

## What is status code 308?

The HyperText Transfer Protocol (HTTP) 308 Permanent Redirect redirect status response code indicates that the resource requested has been definitively moved to the URL given by the Location headers. ... Note: Some Web applications may use the 308 Permanent Redirect in a non-standard way and for other purposes.

## What code would you use if an update didn’t return data to a client?

204 No Content - A proper code for updates that don’t return data to the client, for example when just saving a currently edited document.
 

## What code would you use if a resource used to exist but no longer does?

The HyperText Transfer Protocol (HTTP) 410 Gone client error response code indicates that access to the target resource is no longer available at the origin server and that this condition is likely to be permanent.

## What is the ‘Forbidden’ status code?

The HTTP 403 Forbidden client error status response code indicates that the server understood the request but refuses to authorize it. This status is similar to 401, but in this case, re-authenticating will make no difference.