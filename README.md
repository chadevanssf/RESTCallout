# REST Callout

A framework to make it easier (read less coding) to make REST calls from Salesforce. Currently it supports the following
use cases:

- Input data is taken from a Salesforce Object, REST call is made, result is stored in Salesforce Object
- A list of results is retrieved as REST call and shown using an External Object

## Setup

In order to add the framework to your Salesforce org follow the following steps.

### Deploy the repository to your org

Deploy the contents of this repository to your org by pressing the next button.

<!-- markdownlint-disable MD033 -->
<a href="https://githubsfdeploy.herokuapp.com"><img alt="Deploy to Salesforce"         src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png"></a>
<!-- markdownlint-enable MD033 -->

### Assing Permission Set to relevant user

Assign the 'REST Integration Framework' permission set to a relevant user in your org.

## Desclaimer

Copyright (c) 2017, Jack van Dijk, Sales Engineering, Salesforce.com Inc.
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

- Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
- Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
- Neither the name of the salesforce.com nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES,
INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE,
EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.