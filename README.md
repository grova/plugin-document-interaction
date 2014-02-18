plugin-document-interaction
===========================

IOS UIDocumentInteractionController wrapper 

porting of https://github.com/stringbean/cordova-plugins to build.phonegap

Usage:

window.plugins.documentInteraction.previewDocument(filePath, mimeType, title);

filePath: file path on the local fileSystem
mimeType: optional MIME type. If not specified the plugin will guess based on the file extension.
title: optional title of the controller
