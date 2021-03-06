2.0.0 / 2017-03-01
========================
 * prep for npm publish
 * rename "barry" to "brie"
 * package.json updates for public module

1.0.0 / 2017-02-28
========================
 * added "type" check as "is"
 * Full test suite
 * Full test coverage

0.13.0 / 2017-02-17
========================
 * added "test" command to scripts
 * JiraId: UI-12235 updates lodash dependency from lodash-node to lodash@4.0.0
 * JiraId: UI-12235 updates mocha dependency to 3.2.0-compatible

0.11.0 / 2014-10-07
========================
 * JiraId: UI-1434 corrects bug with allowIDs that fails on strict equality; performs type conversion between string ID and numeric ID

0.10.9 / 2014-09-02
========================
 * JiraId: UI-1240 corrects 0-check for percentMax values

0.10.8 / 2014-08-22
========================
 * JiraId: UI-1206 corrects "check" method exception;
 * JiraId: UI-1206 evaluates feature criteriaLogic;
 * JiraId: UI-1206 moves feature evaluator setup to barry setup method.

0.10.7 / 2014-08-22
========================
 * JiraId: UI-1206 modification in percentScale

0.10.6 / 2014-08-22
========================
 * JiraId: UI-1206 date needs an "equality"

0.10.5 / 2014-08-22
========================
 * JiraId: UI-1206 number needs an "equality"

0.10.4 / 2014-08-22
========================
 * JiraId: UI-1206 method name change; not all data blocks are "user", so not all ID matches are on UserId

0.10.3 / 2014-08-19
========================
 * JiraId: UI-1219 creates blank versions of data concern based on pristine source, then extends a clone.

0.10.2 / 2014-08-19
========================
 * JiraId: UI-1218 string values not being converted to boolean; introduces booleanify method for overrides
 * JiraId: UI-1218 lodash "isEqual" check for empty arrays of criteria response; returns (bool) false by default.

0.10.1 / 2014-08-19
========================
 * JiraId: UI-1211 backs out of "extend" paradigm for overrides.

0.10.0 / 2014-08-19
========================
 * JiraId: UI-1210 allows code to pass "overrides" property with arguments to allFeatures()

0.9.3 / 2014-08-19
========================
 * JiraId: UI-1209 corrects un-handled typecheck in r_engine.  cannot call Object.keys on non-object types

 0.9.2 / 2014-08-18
========================
 * JiraId: UI-1105 Includes a too-aggressive sting-to-date conversion gate, to capture non-object date values.  This leaves some room for improvement.

 0.9.1 / 2014-08-18
========================
 * JiraId: UI-1105 Adds date comparisons for older/newer.

0.8.7 / 2014-08-18
========================
 * JiraId: UI-1105 reverts string comparison for "above" and "below" to strict >= and <= evaluators.  Lexigraphic comparison may cause confusion but is, strictly speaking, the more-expected operation.

0.8.2-0.8.6 / 2014-08-12
========================
 * JiraId: UI-1105 "above" and "below" comparison for object attempts to compare original object to extended object
 * JiraId: UI-1105 adds new comparison for "object"
 * JiraId: UI-1105 adds "above" and "below" for number
 * JiraId: UI-1105 adds "above" and "below" for string

0.8.1 / 2014-08-09
==================
 * JiraId: UI-1105 minor correction in log output

0.8.0 / 2014-08-09
==================
 * JiraId: UI-1105 adds comparison mechanisms for number and string
 * JiraId: UI-1105 converts Barry "has" method to use embedded comparison mechanisms

0.7.0 / 2014-08-08
==================
 * JiraId: UI-1105 adjusts criteria validation to accept an array instead of singleton.  Bolsters engine processing to accurately calculate criteria arrays.
 * JiraId: UI-1105 accommodates criteriaLogic of "any" or "all", using the lodash "some" or "every" methods


0.6.2 / 2014-08-07
==================
 * JiraId: UI-1105 requiring lodash-node instead of undefined "lodash"

0.6.1 / 2014-08-06
==================
 * JiraId: UI-1105 adding history.md
 * JiraId: UI-1105 updating barry logic and bumping minor version

0.5.0 / 2014-08-01
==================

 * JiraId: UI-1133 Added Has method.  Stubbed hasMore and hasFewer.  Logs modification.
 * JiraId: UI-1133 Removed wayward "flags" argument
 * JiraId: UI-1133 ...and bumped minor version

0.4.5 / 2014-07-27
==================

 * JiraId: UI-1105 resolving local data arguments instead of global; fflip always passes context with method calls.
 * JiraId: UI-1105 resolving local data arguments instead of global; fflip always passes context with method calls.

0.4.4 / 2014-07-26
==================
 * JiraId: UI-1105 diagnostics, logging and clean execution
 * JiraId: UI-1105 minor change ==> bump minor version
 * JiraId: UI-1105 building out processing and constructor; drops dependency on RSVP
 * JiraId: UI-1105 requires fflip, RSVP and lodash
 * JiraId: UI-1105 correcting definition in package.json
 * JiraId: UI-1046 defines README for barry
