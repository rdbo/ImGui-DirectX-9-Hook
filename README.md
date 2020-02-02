# ImGui-DirectX-9-Hook
<h1>Setting up the solution</h1>
<ul>
  <li>Download and install <a href="https://www.microsoft.com/en-us/download/details.aspx?id=6812">DirectX SDK</a></li>
  <li>Open the solution on Visual Studio and open the project Properties</li>
  <li>Go to VC++ Directories -> Include Directories. Click on 'Edit' and select the Include folder <br/>located on your DirectX SDK installation path. It is generally this one: <br/><i>%programfiles(x86)%\Microsoft DirectX SDK (June 2010)\Include\</i> or <i>%DXSDK_DIR%\Include\</i>
  <li>Now go to VC++ Directories -> Library Directories. Click on 'Edit' and select the library folder <br/> located on your DirectX SDK installation path. It is generally this one - choose x86 for 32bit and x64 for 64bit: <br/><i>%programfiles(x86)%\Microsoft DirectX SDK (June 2010)\Lib\</i> or <i>%DXSDK_DIR%\Lib\</i></li>
  <li><b>Done!</b></li>
</ul>
