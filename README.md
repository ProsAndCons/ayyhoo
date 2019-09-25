# Ayyhoo-Server

## Usage
###### WIP: ~~Absolutely nothing works yet.~~ Login works!

Use [Yahoo! Messenger v5.5.1228](http://www.oldversion.com/windows/yahoo-messenger-5-5-1228), or a client that supports YMSG protocol v9/10

Using regedit, find HKEY_CURRENT_USER\Software\Yahoo\Pager in Windows Registry, and modify socket server to the IP/host of desired server

## Development
Some helpful resources that were used to understand the protocol better and make development possible 

> [JYMSG](http://jymsg9.sourceforge.net/)
>
>   Overall best source for our purposes, implements v9/10 of the protocol in easy to understand code. 
>
> [libyahoo2](http://libyahoo2.sourceforge.net/)
>
>   Whole source code for client, and some documentation for v9 of the protocol I'm trying to implement
v9 is implemented in libyahoo2-0.7.0 version. 
>
> [YMSG-Protocol](https://gitlab.com/valtron/msn-server/wikis/YMSG-Protocol)
>
>   Overview of the development of the protocol and differences in versions. 
>
> [ycoderscookbook](http://web.archive.org/web/20100924153734/http://www.ycoderscookbook.com/tutorials/)
>
>   Old-school tutorial originally for exploiting the protocol, site no longer exists but web archive is available and has most of the useful info. 
