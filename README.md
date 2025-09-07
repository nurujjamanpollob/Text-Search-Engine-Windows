# Text-Search-Engine-Windows

 <p>
        This project is a powerful, intuitive tool designed to help developers and users manage and modify files across their systems. It combines system-wide text searching with the advanced capabilities of a large language model (LLM) to perform complex file modifications from a user-friendly interface. Best of all, it's completely free to use.
    </p>

<h2>Features</h2>
    <ul>
        <li><strong>System-wide Text Matching:</strong> Efficiently search for specific text strings or patterns within any file on your system.</li>
        <li><strong>Smart LLM Integration:</strong> Connect to a powerful LLM to understand and interpret your modification requests.</li>
        <li><strong>Intuitive Interface:</strong> A clean, easy-to-use interface allows you to define your desired changes without writing complex scripts.</li>
        <li><strong>Intelligent File Modification:</strong> The LLM analyzes your request, identifies the relevant files from the text search, and makes the necessary modifications, all based on natural language instructions.</li>
     <li><strong>Work as a project:</strong> Open a folder as a project, edit files with AI inline code suggestion, ship faster</li>
     <li><strong>Works completely offline:</strong> This editor can work without any activation or internet access, so you can build with confidence and privacy</li>
        <li><strong>Free and Open-Source:</strong> Access all features for free, with the potential for community contributions to enhance functionality.</li>
    </ul>

  <h2>Getting Started</h2>
    <p>

   Note: if you are upgrading from version 1.0 or 1.1 to 2.0 beta, uninstall any previous version installed.
        Download the Windows Installer from the <a href="https://github.com/nurujjamanpollob/Text-Search-Engine-Windows/releases">release page</a>. This application requires TCP port 8080 to be free to run the file management server. 
   </p>
    <p>

   <h2> Using AI function </h2>

 This application supports custom OpenAI-like endpoint. You need to configure the endpoint from the AI settings page. 
 The custom OpenAI endpoint implementation tested working with LM studio. If you use LM Studio as an AI provider, follow below instruction for easy configuration:

 <b>For Version 2.0</b>

 You'll need to have LM Studio installed. Link here: <a href="https://lmstudio.ai/">LM Studio</a>. Once installed, download your favorite AI model. Then close LM studio, 
 and launch the Eaze Text Editor. After opening, wait for 3-4 seconds to let the system detect LM studio integration. Once detected, A pop-up will appear, so enable LM studio integration. 
 Once you enable integration and you will also be asked to set a Custom OpenAI endpoint automatically to connect with the LM studio's provided custom OpenAI endpoint.
 Hit "Yes" and you will have a working LM studio integration out of the box!

  <b>For Version 1.1 beta and earlier</b>
     
  You'll need to have LM Studio installed. Link here: <a href="https://lmstudio.ai/">LM Studio</a>. Once installed, download your favorite AI model, and then enable the API function from LM studio settings, and don't forget to enable CORS settings from the API settings.
  As this is an old version, it doesn't have any integration with LM studio, you have to open and close the AI service manually from the LM studio software.
  </p>

  <p>Enjoy!</p>

  <h2>Version Log</h2>

 Version 2.0[beta]

All previous improvements from version 1.1[beta]

Plus, New Improvements: 
  
  <ul>
   <li>Found search performance bottleneck and fixed it, much faster search now.</li>
   <li>Files sort function.</li>
   <li>Open Folder as a project button</li>
   <li>Folder and File structure in the text editor got enhanced.</li>
   <li>Added LM studio direct integration support for offline AI model management and application state management.</li>
   <li> Added Inline code completion with AI </li>
   <li> Make the editor work completely offline </li>
   <li> Update UI bug where AI chat shows stop button still, despite the chat request failing with an HTTP non-200 code </li>
   <li> UI and navigation enhancements </li>
  <li> Added server and integration management settings </li>
   <li> Some more minor improvements</li>
  </ul>
  
  Future plans:
  
  <ul>
  <li> Add AI agent function, will automatically code, test, compile, ship </li>
  <li> Code Syntax Validation </li>
  <li> Compiler and Shell integration </li>
  <li> Train AI on Codebase for better code suggestion functionality </li>
  <li> Release for more platforms: Mac and Linux</li>
  </ul>


   Version 1.1[beta]: 
  
  <ul>
   <li>50-100x search Speed boost[beta]</li>
   <li>Search Session Restore functionality[Beta]</li>
   <li>Fix Windows Installer, now uninstaller clears all directories </li>
   <li>File Management server stop function[beta]</li>
  </ul>

  First Version: 
  
  <ul><li>Stable release.</li></ul>
  
  <h2> Download</h2>  
  
  Version 2.0[beta] : <a href="https://github.com/nurujjamanpollob/Text-Search-Engine-Windows/releases/download/version-1.1-win-x86_64/TextSearchEngineInstaller.exe">TextSearchEngineInstaller V 2.0.exe</a>

  Version 1.1[beta] : <a href="https://github.com/nurujjamanpollob/Text-Search-Engine-Windows/releases/download/version-1.1-win-x86_64/TextSearchEngineInstaller.exe">TextSearchEngineInstaller V 1.1.exe</a>

   First version : <a href="https://github.com/nurujjamanpollob/Text-Search-Engine-Windows/releases/download/version-1.0.0-win-x86_64/TextSearchEngineInstaller.exe">TextSearchEngineInstaller V 1.0.exe</a> <br><br>

  
