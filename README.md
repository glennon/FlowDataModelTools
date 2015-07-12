FlowDataModelTools
==================

Description: a set of circa 2006 ArcGIS VB macros to create flow lines from a OD matrix. You basically just load up the .mxd file into ArcGIS and make the macros a tool. Replaced by [flowpyGIS](http://github.com/glennon/FlowpyGIS). The old support website can be found on archive.org at: https://web.archive.org/web/20130427134141/http://dynamicgeography.ou.edu/flow

==================

Flow Data Model Tools
License

Update #1, 10/2009: Due to the problem noted in Update #2, I reprogrammed the flow tools as a Python script. As such, the Flow Data Model Tools are now deprecated. Those tools still work, but are exceedingly quirky. To download and use Flowpy, visit: http://enj.com/software.

Update #2, 7/2008: The software broke in 9.2/9.3, so we hardcoded an unsavory workaround to make it work.
To make the flow tools work, your files and output must be in the directory: "C:\temp\flow\"

Update #3, 15 June 2013: If you're looking for FlowpyGIS, head over to its github repo: https://github.com/glennon/FlowpyGIS. Any updates new stuff will be hosted on github. Its previous home (enj.com/software) will probably be repurposed before too long. I suppose I should update the license too. For now, enjoy the nostalgia of all caps. Be aware that the latest versions of ArcGIS no longer support VBA, so the FDMT scripts are virtually useless. Again, they are provided here only as an archive.

==================

Copyright © 2004-2008 J. Alan Glennon, Department of Geography, University of California, Santa Barbara, CA 93106. All Rights Reserved.

This software is subject to the following License Agreement. Please read and agree to all terms before using the software. By using the FLOW DATA MODEL TOOLS software (the Software), you are consenting to be bound by this agreement. If you do not agree to all of the terms of this agreement, do not use the software.

'* Flow Data Model Tools
'* Copyright © 2004-2008 J. Alan Glennon, Department of Geography,
'* University of California, Santa Barbara, CA 93106. All Rights Reserved.
'*
'*
'* Redistribution and use in source and binary forms, with or without
'* modification, are permitted provided that the following conditions are met:
'* * Redistributions of source code must retain the above copyright
'* notice, this list of conditions and the following disclaimer.
'* * Redistributions in binary form must reproduce the above copyright
'* notice, this list of conditions and the following disclaimer in the
'* documentation and/or other materials provided with the distribution.
'* * Neither the name of Alan Glennon, University of California, nor the
'* names of its contributors may be used to endorse or promote products
'* derived from this software without specific prior written permission.
'*
'* THIS SOFTWARE IS PROVIDED BY ALAN GLENNON ``AS IS'' AND ANY
'* EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
'* WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
'* DISCLAIMED. IN NO EVENT SHALL ALAN GLENNON BE LIABLE FOR ANY
'* DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
'* (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
'* LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
'* ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
'* (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
'* SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
