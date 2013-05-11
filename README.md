## Introduction

    **AXYNC** (**A**utomatic OS **X** RS**YNC**)

    Watch filesystem paths and start rsync on any changes.

    Usage: **axync <command> <arguments>**** where command and arguments are:
    **list**
 
    List the currently active axync watches with their IDs.

    **start [<options>] <local>... <remote>**

    Transfer <local> paths immediately to <remote> with rsync. <options> are passed to rsync unchanged. If this is successful install a file system watcher and rerun same transfer whenever a file changes.

    **stop {<pid>}**

    Stop the watcher(s). The PIDs are listed in command **list**.

    **stopall**

    Stop all watchers.

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
