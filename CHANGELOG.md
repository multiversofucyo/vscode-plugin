# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

<!-- PRs should document any user-visible changes here. -->

## [0.2.0] - 2016-11-21

### Fixed

* Updated to v1.1.1 of the editor service. This comes with some stability improvements, including:
  * better handle errors when detecting Polymer Behaviors
  * handle cyclic dependency graphs
  * See the editor service changelog for more: https://github.com/Polymer/polymer-editor-service/blob/master/CHANGELOG.md#111---2016-11-21

## [0.1.2] - 2016-10-26

### Added
* Add an icon.

### Fixed
* Internal errors no longer cause an intrusive popup. They instead log to the plugin's output tray.

## [0.1.1] - 2016-10-25

### Fixed
* Fix Windows support, as well as projects with paths with characters that need URL escaping (e.g. spaces). #17 #23 #28

## [0.1.0] - 2016-10-17

### Added
* Initial public release!
* Support contextual autocompletion of custom element tags and attribute names.
  * Also display docs in autocomplete for both.
* Support getting documentation popups on hover.
* Support jump to definition of custom elements and their attributes.
* Knows how to recognize:
 * Vanilla Custom Element v1 definitions.
 * Polymer 1.0 element declarations.
 * Partial support for Polymer 2.0 element declarations.
