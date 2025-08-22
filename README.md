<IfModule mod_mono.c>
    MonoAutoApplication enabled
    AddHandler mono .aspx .ashx .asmx .ascx .aspx .config .cs .asmx
    MonoServerPath /usr/bin/mod-mono-server4
</IfModule>
<configuration>
  <system.web>
    <compilation debug="true" targetFramework="4.7.2" />
    <httpRuntime targetFramework="4.7.2" />
  </system.web>
</configuration>
