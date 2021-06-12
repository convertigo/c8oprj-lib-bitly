# lib_Bitly
This is the Bitly library for Convertigo platform. Use this library to shorten urls

# Installation

* In your Convertigo Studio use File->Import->Convertigo->Convertigo Project and hit the 'Next' button

* In the Dialog 'Project remote URL' field Paste :

        lib_Bitly=https://github.com/convertigo/c8oprj-lib-bitly.git

* And click the 'Finish' button
* Create all 'Undefined Global Symbols' when prompted

# Usage

## How to get your API Key

This library is based on Bitly API, to access this API:

* Go to https://bitly.is/accesstoken 
* Login to your Bitly account. If you do not have a bitly account create one. A free one works ok for 1000 links / month
* On the right hand side you will see GENERIC ACESS TOKEN panel. Follow instructions and click GENERATE TOKEN button
* Copy your API key

## Configuring Convertigo Symbols

__lib_Bitly__ needs some symbols to be configured. You configure them through the Web Console: **https://&lt;your site&gt;.convertigo.net/admin**, hit the ___symbols___ button to get to the symbol configuration page.

Symbol  | value
------| ------
lib_Bitly.token.secret | Your **TOKEN** value you copied from previous step

## Sequences

__lib_Bitly__ provides sequences you can call in your projects

Sequence  | Action
------| ------
Shorten | Shortens an url <br />


#### Object returned
| Name        | Type           | Default 
| ------------- |-------------| -----|
| **link**      | string | *The shortened link* |


