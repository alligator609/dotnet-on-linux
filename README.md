1. check ubuntu version to see compatible dotnet sdk. command -\&gt; lsb\_release -a
2. Installing with APT can be done with a few commands. Before you install .NET, run the following commands to add the Microsoft package signing key to your list of trusted keys and add the package repository.

  - wget https://packages.microsoft.com/config/ubuntu/21.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
  - sudo dpkg -i packages-microsoft-prod.deb
  - rm packages-microsoft-prod.deb
- The .NET SDK allows you to develop apps with .NET. If you install the .NET SDK, you don&#39;t need to install the corresponding runtime. To install the .NET SDK, run the following commands:

  - sudo apt-get update; \ sudo apt-get install -y apt-transport-https &amp;&amp; \ sudo apt-get update &amp;&amp; \ sudo apt-get install -y dotnet-sdk-5.0
- To see if nginx is running
  - sudo service nginx status
-