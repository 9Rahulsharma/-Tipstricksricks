[00:00:00] Build started
[00:00:00] git clone -q https://github.com/codecadwallader/codemaid.git C:\projects\codemaid
[00:00:03] git fetch -q origin +refs/pull/912/merge:
[00:00:03] git checkout -qf FETCH_HEAD
[00:00:04] Running Install scripts
[00:00:04] (new-object Net.WebClient).DownloadString("https://raw.github.com/madskristensen/ExtensionScripts/master/AppVeyor/vsix.ps1") | iex
[00:00:04] Patching AssemblyInfo
[00:00:04] Patching CodeMaid\Properties\AssemblyInfo.cs...OK
[00:00:04] Patching CodeMaid.UnitTests\Properties\AssemblyInfo.cs...OK
[00:00:04] Patching CodeMaid.VS2022\Properties\AssemblyInfo.cs...OK
[00:00:04] Patching GlobalAssemblyInfo.cs...OK
[00:00:04] nuget restore
[00:00:05] MSBuild auto-detection: using msbuild version '16.11.2.50704' from 'C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\MSBuild\Current\Bin'.
[00:00:10] Restoring packages for C:\projects\codemaid\CodeMaid.UnitTests\CodeMaid.UnitTests.csproj...
[00:00:10] Restoring packages for C:\projects\codemaid\CodeMaid\CodeMaid.csproj...
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/mstest.testadapter/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/mstest.testframework/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/expression.blend.sdk/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.net.test.sdk/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.sdk/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/nsubstitute/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/nunit/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/nunit3testadapter/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.vssdk.buildtools/index.json
[00:00:11]   OK https://api.nuget.org/v3-flatcontainer/mstest.testadapter/index.json 54ms
[00:00:11]   OK https://api.nuget.org/v3-flatcontainer/nsubstitute/index.json 67ms
[00:00:11]   OK https://api.nuget.org/v3-flatcontainer/nunit/index.json 67ms
[00:00:11]   OK https://api.nuget.org/v3-flatcontainer/mstest.testframework/index.json 71ms
[00:00:11]   OK https://api.nuget.org/v3-flatcontainer/expression.blend.sdk/index.json 79ms
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/mstest.testadapter/2.2.7/mstest.testadapter.2.2.7.nupkg
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/nsubstitute/4.2.2/nsubstitute.4.2.2.nupkg
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/mstest.testframework/2.2.7/mstest.testframework.2.2.7.nupkg
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/nunit/3.13.2/nunit.3.13.2.nupkg
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/expression.blend.sdk/1.0.2/expression.blend.sdk.1.0.2.nupkg
[00:00:11]   OK https://api.nuget.org/v3-flatcontainer/nunit/3.13.2/nunit.3.13.2.nupkg 19ms
[00:00:11]   OK https://api.nuget.org/v3-flatcontainer/microsoft.net.test.sdk/index.json 134ms
[00:00:11]   OK https://api.nuget.org/v3-flatcontainer/mstest.testadapter/2.2.7/mstest.testadapter.2.2.7.nupkg 24ms
[00:00:11]   OK https://api.nuget.org/v3-flatcontainer/mstest.testframework/2.2.7/mstest.testframework.2.2.7.nupkg 20ms
[00:00:11]   OK https://api.nuget.org/v3-flatcontainer/expression.blend.sdk/1.0.2/expression.blend.sdk.1.0.2.nupkg 13ms
[00:00:11]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.sdk/index.json 137ms
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.net.test.sdk/17.0.0/microsoft.net.test.sdk.17.0.0.nupkg
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.sdk/16.10.31321.278/microsoft.visualstudio.sdk.16.10.31321.278.nupkg
[00:00:11]   OK https://api.nuget.org/v3-flatcontainer/nsubstitute/4.2.2/nsubstitute.4.2.2.nupkg 34ms
[00:00:11]   OK https://api.nuget.org/v3-flatcontainer/nunit3testadapter/index.json 150ms
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/nunit3testadapter/4.0.0/nunit3testadapter.4.0.0.nupkg
[00:00:11]   OK https://api.nuget.org/v3-flatcontainer/microsoft.net.test.sdk/17.0.0/microsoft.net.test.sdk.17.0.0.nupkg 36ms
[00:00:11]   OK https://api.nuget.org/v3-flatcontainer/nunit3testadapter/4.0.0/nunit3testadapter.4.0.0.nupkg 27ms
[00:00:11]   OK https://api.nuget.org/v3-flatcontainer/microsoft.vssdk.buildtools/index.json 221ms
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.vssdk.buildtools/16.11.35/microsoft.vssdk.buildtools.16.11.35.nupkg
[00:00:11]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.sdk/16.10.31321.278/microsoft.visualstudio.sdk.16.10.31321.278.nupkg 110ms
[00:00:11]   OK https://api.nuget.org/v3-flatcontainer/microsoft.vssdk.buildtools/16.11.35/microsoft.vssdk.buildtools.16.11.35.nupkg 12ms
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.embeddable/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.imaging/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.imagecatalog/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/envdte100/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.commandbars/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.debugger.interop.12.0/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.debugger.interop.14.0/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.debugger.interop.15.0/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.debugger.interop.16.0/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.designer.interfaces/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.ole.interop/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.projectaggregator/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.immutable.10.0/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.immutable.11.0/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.immutable.12.0/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.immutable.14.0/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.15.1.designtime/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.15.5.designtime/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.15.7.designtime/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.15.8.designtime/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.16.0.designtime/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.16.1.designtime/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.16.10.designtime/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.16.2.designtime/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.16.3.designtime/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.16.4.designtime/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.16.5.designtime/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.16.6.designtime/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.16.7.designtime/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.16.9.designtime/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.textmanager.interop.12.1.designtime/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.vshelp80/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.wcfreference.interop/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/castle.core/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.codecoverage/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/vslangproj100/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/vslangproj150/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/vslangproj157/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/vslangproj158/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/vslangproj165/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/vslangproj2/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.design/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.package.languageservice.15.0/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.texttemplating.15.0/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.texttemplating.interfaces.15.0/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.texttemplating.vshost.15.0/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.componentmodelhost/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.coreutility/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.editor/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.language/index.json
[00:00:11]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.imagecatalog/index.json 83ms
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.language.intellisense/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.language.navigateto.interfaces/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.language.standardclassification/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.languageserver.client/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.sdk.analyzers/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.sdk.embedinteroptypes/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.taskrunnerexplorer.14.0/index.json
[00:00:11]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.text.logic/index.json
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.web.browserlink.12.0/index.json
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.imagecatalog/16.10.31320.204/microsoft.visualstudio.imagecatalog.16.10.31320.204.nupkg
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/system.componentmodel.composition/index.json
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.embeddable/index.json 118ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.16.0.designtime/index.json 86ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.codecoverage/index.json 68ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/envdte100/index.json 116ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/castle.core/index.json 70ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.imagecatalog/16.10.31320.204/microsoft.visualstudio.imagecatalog.16.10.31320.204.nupkg 24ms
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.embeddable/16.10.31320.204/microsoft.visualstudio.shell.embeddable.16.10.31320.204.nupkg
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.16.0.designtime/16.10.31320.204/microsoft.visualstudio.shell.interop.16.0.designtime.16.10.31320.204.nupkg
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/envdte100/16.10.31320.204/envdte100.16.10.31320.204.nupkg
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/microsoft.codecoverage/17.0.0/microsoft.codecoverage.17.0.0.nupkg
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/castle.core/4.4.0/castle.core.4.4.0.nupkg
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.embeddable/16.10.31320.204/microsoft.visualstudio.shell.embeddable.16.10.31320.204.nupkg 25ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.16.0.designtime/16.10.31320.204/microsoft.visualstudio.shell.interop.16.0.designtime.16.10.31320.204.nupkg 23ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.debugger.interop.16.0/index.json 146ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.immutable.14.0/index.json 136ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.commandbars/index.json 173ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.immutable.12.0/index.json 155ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.designer.interfaces/index.json 169ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.codecoverage/17.0.0/microsoft.codecoverage.17.0.0.nupkg 35ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.debugger.interop.15.0/index.json 175ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/castle.core/4.4.0/castle.core.4.4.0.nupkg 34ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.imaging/index.json 183ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.immutable.11.0/index.json 163ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.15.1.designtime/index.json 161ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.ole.interop/index.json 176ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.15.8.designtime/index.json 173ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.16.3.designtime/index.json 169ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.16.1.designtime/index.json 180ms
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.debugger.interop.16.0/16.10.31320.204/microsoft.visualstudio.debugger.interop.16.0.16.10.31320.204.nupkg
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.16.4.designtime/index.json 177ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.16.9.designtime/index.json 172ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.wcfreference.interop/index.json 168ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop/index.json 182ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/vslangproj100/index.json 162ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.package.languageservice.15.0/index.json 153ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/vslangproj158/index.json 160ms
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.commandbars/16.10.31320.204/microsoft.visualstudio.commandbars.16.10.31320.204.nupkg
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/vslangproj165/index.json 164ms
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.immutable.12.0/16.10.31321.278/microsoft.visualstudio.shell.immutable.12.0.16.10.31321.278.nupkg
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.componentmodelhost/index.json 157ms
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.immutable.14.0/16.10.31321.278/microsoft.visualstudio.shell.immutable.14.0.16.10.31321.278.nupkg
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.texttemplating.15.0/index.json 162ms
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.debugger.interop.15.0/16.10.31320.204/microsoft.visualstudio.debugger.interop.15.0.16.10.31320.204.nupkg
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.imaging/16.10.31321.278/microsoft.visualstudio.imaging.16.10.31321.278.nupkg
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.immutable.11.0/16.10.31321.278/microsoft.visualstudio.shell.immutable.11.0.16.10.31321.278.nupkg
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.15.1.designtime/16.10.31320.204/microsoft.visualstudio.shell.interop.15.1.designtime.16.10.31320.204.nupkg
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.ole.interop/16.10.31320.204/microsoft.visualstudio.ole.interop.16.10.31320.204.nupkg
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.16.3.designtime/16.10.31320.204/microsoft.visualstudio.shell.interop.16.3.designtime.16.10.31320.204.nupkg
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.15.8.designtime/16.10.31320.212/microsoft.visualstudio.shell.interop.15.8.designtime.16.10.31320.212.nupkg
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.16.1.designtime/16.10.31320.204/microsoft.visualstudio.shell.interop.16.1.designtime.16.10.31320.204.nupkg
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.16.4.designtime/16.10.31320.204/microsoft.visualstudio.shell.interop.16.4.designtime.16.10.31320.204.nupkg
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.web.browserlink.12.0/index.json 158ms
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.designer.interfaces/16.10.31320.204/microsoft.visualstudio.designer.interfaces.16.10.31320.204.nupkg
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.coreutility/index.json 174ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.shell.interop.15.7.designtime/index.json 230ms
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.wcfreference.interop/16.10.31320.204/microsoft.visualstudio.wcfreference.interop.16.10.31320.204.nupkg
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/envdte100/16.10.31320.204/envdte100.16.10.31320.204.nupkg 128ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.text.logic/index.json 166ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/microsoft.visualstudio.language.standardclassification/index.json 172ms
[00:00:12]   OK https://api.nuget.org/v3-flatcontainer/system.componentmodel.composition/index.json 147ms
[00:00:12]   GET https://api.nuget.org/v3-flatcontainer/vslangproj100/16.10.31320.20

