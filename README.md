README
==========================================

This toolset allows you to convert UML sequence+activity diagrams into mCRL2 process algebra descriptions and vice-versa.
Currently it's split into two tools, each responsible for one direction in the conversion process.

========= UML-> mCRL2 ========

The UML2mCRL2 tool requires that you have a *.uml file exported in XMI format from your favorite UML tool. All the Eclipse’s MDT-UML2 plugin
jars which the tool uses, have been exported together, so you should not experience dependencies problems.

usage:

$ java -jar UML2mCRL2.jar [/path/to/your/file.uml]

=========mCRL2 trace -> UML =====================

The mCRL22UML tool requires that you have a *.trc file containing the mcRL2 trace (pretty-print with tracepp). 

usage:

$java -jar mCRL22UML.jar [/path/to/traceFile.trc] [outputModel.uml]

=================================================

In this repo you will also find examples of exported UML models, as well as generated mCRL2 models and traces.
