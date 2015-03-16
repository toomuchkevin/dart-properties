<p>The project aim is to provide a very simple and lightweight implementation of properties file management for Dart. Code and usage are very straightforward. To get started just have a look at the unit tests provided along with the source code.</p>

## Quick start ##
Have a check here: http://pub.dartlang.org/packages/properties

## Release history ##

### 0.5.3 ###
Fixed error on Event.<br>
Fixed carriage return problem on line parsing.<br>
Minor code improvements on merge and other.<br>
Deprecated enable/disable events triggering.<br>

<h3>0.5.2+1 - 21-03-2013</h3>
Compatibility update for SDK 0.4.2<br>

<h3>0.5.2 - 21-03-2013</h3>
Fixed a bug on merge methods, now managing existing empty properties without overwriting them in any case.<br>
Improved testing on merge methods.<br>
Now managing special characters for values decoding as UTF-8 the bytes read from file.<br>

<h3>0.5 - 16-03-2013</h3>
Now files are read as bytes enabling deeper property management features.<br>
Added multi-line value support.<br>
Now the first non-escaped equal is parsed as key-value separator.<br>
Added getBool method with customizable evaluator.<br>
Minor doc improvements.<br>
Unit tests improvements.<br>

<h3>More details about older versions?</h3>
Have a check on the CHANGELOG file.<br>
<br>
<br>
<h2>What's next</h2>
<p>
<ul><li>Output properties to file<br>
</li><li>Read properties from xml<br>
</p>