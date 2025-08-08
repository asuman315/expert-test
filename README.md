Repo: https://github.com/asuman315/expert-test

## Overview
This document outlines the major bugs that were discovered and resolved in the Scheduling App

## Critical Fixes Implemented

### Isuue One
 **Error** : `Error sending confirmation email: FunctionsFetchError: Failed to send a request to the Edge Function`
**Severity**: Critical
**Status**: Fixed

#### Problem
I think we lacked the Resend API Key - `RESEND_PUBLIC_KEY`

#### Fix
Created a supabase account and Resend account which I connected to the project.


### Issue two
**Error** : `Error generating personalized content: TypeError: Cannot read properties of undefined (reading '0')\n    at generatePersonalizedContent`
**Severity**: Critical
**Status**: Fixed


#### Problem
We lacked the OPEN AI API Key - `OPENAI_API_KEY`

#### Fix
Created a supabase and Resend account which I connected to the project.


### Issue three
**Error** : `The was a bad user experience on clicking of the Get Early Access button`
**Severity**: Moderate
**Status**: Fixed

### Problem
There was no loading state on the `Get Early Access` button so user would not know whether they clicked on the button or not

### Fix
Add a loading state to the button `Get Early Access` after I click the button 
 




