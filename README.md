## Description
This is a set of tools to improve some common functionality and workflow processes of managing HAK5's BashBunny.

## Installation
All scripts should be copied to `/tools`, on the BashBunny, and can be executed from the serial console or within payload scripts.

## The Meat & Potatos

* bdisk: This is a tool to quickly format and setup a new SDCard on the BashBunny - targeting the MARK II.
* bmount: Little more efficent than the standard `udisk` tool, allowing you to simultaneously mount both the SDCard and internal flash.
* bsync: A tool to sync flash/sdcard contents and copy tools quickly to `/tools`.