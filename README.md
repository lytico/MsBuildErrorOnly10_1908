# MsBuildErrorOnly10_1908

repo to reproduce the following error:

on linux mono with monodevelop

if you create a solution with more than 10 projects
the following error occurs:

<code>
Getting restore information for solution /data/Projects/MsBuildErrorOnly10/test11/test11.sln
ApplicationName='/usr/bin/mono64', CommandLine='"/usr/lib/mono/msbuild/15.0/bin/MSBuild.dll" "/tmp/NuGetScratch/anmzxi2p.xaq.nugetinputs.targets" /t:GenerateRestoreGraphFile /nologo /nr:false /v:q /p:RestoreBuildInParallel="False" /p:RestoreUseSkipNonexistentTargets="False"', CurrentDirectory='/data/Projects/MsBuildErrorOnly10/test11', Native error= Cannot find the specified file
</code>
