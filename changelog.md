# CHANGELOG TEMPLATE
All notable changes to this project will be documented in this file.  
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),  
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).  

## [Unreleased]
- Keep an Unreleased section at the top to track upcoming changes.
- **This serves two purposes:**
- People can see what changes they might expect in upcoming releases
- At release time, you can move the Unreleased section changes into a new release version section.

## [Version:Major.Minor.Patch:(SemVer-2.0)] - [Date:YYYY-MM-DD]
### Sub-Section
- List out all the changed done in the above sub-section
- All the changes are versioned according to the SemVer-2.0 specifications mentioned in the RC/CZ CM-Management
- All the major changes should always be highlighted in the first points of the respective sections
- If it is `Added` sub-section, then you can mention the new files, features, changes added in this version
- If it `Removed` sub-section, then you can mention the files, feature, contents removed in th current version, etc.
- If there are multiple types of tasks done like adding new change, updating few others, etc. then you should create sub-sections accordingly and list out them aptly
-----------------------------------------------------------------------------------------------------------

# SAMPLE CHANGELOG
All notable changes to this project will be documented in this file.  
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),  
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).  

## [Unreleased]
- Spring Security to be added with BCryptPasswordEncoder
- Password Encoding/Decoding logic to be added using JSON Web Tokens


## [0.1.9] - [2019-11-01]
### Added
- Spring Security module added for all public APIs...
- Delete User Profile data API added...

### Updated
- SSL Certificate for the QA/PREPROD updated...
- Encryption/Decryption class logic abstracted...


## [0.1.8] - [2019-10-14]
### Fixed
- T056 **fixed** for database connection exception handling
- T009 **fixed** for user credential manager exception on blank username & password

### Removed
- Sanity API removed alognwith all related BDDs
-----------------------------------------------------------------------------------------------------------

# Glossary  

## Sub-Sections
The following sections denotes the type of change received in the marked version.  
The style followed for this tag is Level-3 Heading & always succeeds the `Version` section
1. Added : Section denoting the new changes added in the current version
2. Removed : Section denoting the content that is removed in the current version
3. Updated : Section denoting the content been updated in the current version
4. Fixed : Section denoting the content or feature that has received a fix in the current version
