NAME = $(shell basename $(shell pwd))
PATCH = contacts/${NAME}.patch
TWEAKS =
TITLE = Sync Fix for Google Contacts
DESCRIPTION = This patch fix sync issue for google contactsIssues fixed: * Upload contacts with non-ASCII characters like Chinese * Upload contacts for field with only space characterIssues not fixed yet: * Some non-ASCII character corrupted randomly. When this happen, every bytes of the UTF-8 character is recognized as a character
CATEGORY = Contacts
VERSIONS = 2.1.0-202 2.1.1-22 2.1.2-31 2.2.0-100 2.2.3-93 2.2.4-4 3.0.2-84 3.0.4-48
ICON = http://www.webos-internals.org/images/c/ca/Icon_WebOSInternals_Patches_Contacts.png
SCREENSHOTS =
META_SUB_VERSION = 1

include ../common.mk

include ../modifications.mk

MAINTAINER = moo <moo.tinys@gmail.com>
HOMEPAGE =