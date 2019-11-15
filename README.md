<?xml version="1.2" encoding="UTF-8" standalone="yes"?>
<addon id="plugin.video.ELETRONICACENTRAL"
       name="[COLOR white][B]ELETRÔNICA CENTRAL[/B][/COLOR]"
       version="1.1"
       provider-name="arifelcris">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
    <import addon="script.module.beautifulsoup" version="3.2.1"/>
    <import addon="script.module.simple.downloader" version="0.9.4"/>
    <import addon="script.module.beautifulsoup4" />
    <import addon="script.module.requests" />
    <import addon="script.module.httplib2" />
    <import addon="script.module.liveresolver" version="0.1.24" optional="true"/>
    <import addon="script.module.youtube.dl" optional="true"/>
    <import addon="plugin.video.youtube" optional="true" />
	<import addon="plugin.video.SportsDevil" optional="true" />
    <import addon="script.module.urlresolver" optional="true"/>
    <import addon="script.module.simplejson" />    
     <import addon="script.module.livestreamer" optional="true"/>
     <import addon="script.module.pyamf" optional="true"/>
  </requires>
  <extension point="xbmc.python.pluginsource" library="default.py">
    <provides>video</provides>
  </extension>
  
  	
  <extension point="xbmc.addon.metadata">
    <summary>ELETRÔNICA CENTRAL</summary>
    <description>
	[COLOR lime][B]O addon ELETRÔNICA CENTRAL é apenas um AGREGADOR de links e, assim como o Google.com, apenas agrega e organiza os links externos. Não somos responsáveis pelos arquivos aqui encontrados.[/COLOR][/B]
             
    </description>
    <platform>all</platform>
  </extension>
</addon>
