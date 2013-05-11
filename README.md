## Introduction

When developing I would like to push changes to the development server as 
soon as I saved them. I used jEdit for a long time because it has a good sftp
plugin giving me the feeling that the file is local. When I switched to 
Sublime Text 2, I found the sftp plugin not very practical. I decided to write
my own wrapper but outside of any editor.

## Usage

<pre>
<b>AXYNC</b> (<b>A</b>utomatic OS <b>X</b> RS<b>YNC</b>)

Watch filesystem paths and start rsync on any changes.

Usage: <b>axync &lt;command> &lt;arguments></b> where command and arguments are:

  <b>list</b>
    List the currently active axync watches with their IDs.

  <b>start [&lt;options>] &lt;local>... &lt;remote></b>
    Transfer &lt;local> paths immediately to &lt;remote> with rsync. &lt;options>
    are passed to rsync unchanged. If this is successful install a file system
    watcher and rerun same transfer whenever a file changes.

  <b>stop {&lt;pid>}</b>
    Stop the watcher(s). The PIDs are listed in command <b>list</b>.

  <b>stopall</b>
    Stop all watchers.
</pre>

## MIT License

    Copyright Daniel Ly. All rights reserved.
    
    Permission is hereby granted, free of charge, to any person obtaining
    a copy of this software and associated documentation files (the
    'Software'), to deal in the Software without restriction, including
    without limitation the rights to use, copy, modify, merge, publish,
    distribute, sublicense, and/or sell copies of the Software, and to
    permit persons to whom the Software is furnished to do so, subject to
    the following conditions:

    The above copyright notice and this permission notice shall be
    included in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
    EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
    MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
    IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
    CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
    TORT OR OTHERWISE, ARIS
