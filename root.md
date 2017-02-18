<!--
    This Source Code Form is subject to the terms of the Mozilla Public
    License, v. 2.0. If a copy of the MPL was not distributed with this
    file, You can obtain one at http://mozilla.org/MPL/2.0/.
-->

<!--
    Copyright (c) 2014, Joyent, Inc.
-->

# 1.3.6.1.4.1.38678
Joyent OID Root

## 1.3.6.1.4.1.38678.1
LDAP objects

(Also used as the UFDS "hidden" control)

## 1.3.6.1.4.1.38678.1.1
LDAP controls

### 1.3.6.1.4.1.38678.1.1.1
UFDS "hidden" control, if it can every be renamed

### 1.3.6.1.4.1.38678.1.1.3
UFDS set changelog source request

### 1.3.6.1.4.1.38678.1.1.4
UFDS set changelog source response

### 1.3.6.1.4.1.38678.1.1.5
UFDS update checkpoint request

### 1.3.6.1.4.1.38678.1.1.6
UFDS update checkpoint response

### 1.3.6.1.4.1.38678.1.1.7
Request ID hint

## 1.3.6.1.4.1.38678.1.2
LDAP/X.509 attribute types

## 1.3.6.1.4.1.38678.1.3
LDAP ObjectClasses

## 1.3.6.1.4.1.38678.1.4
extKeyPurposes for X.509. Used to restrict usage of keys + certificates used
for TLS client auth with Joyent services.

### 1.3.6.1.4.1.38678.1.4.1
Marks a certificate only for use with `sdc-docker`. MUST not be combined with
any other extKeyPurpose OIDs.

### 1.3.6.1.4.1.38678.1.4.2
Marks a certificate only for use with `cmon`. MUST not be combined with
any other extKeyPurpose OIDs.
