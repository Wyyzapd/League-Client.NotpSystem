# League-Client.NotpSystem
Remove: ZH-CN Tencent Protect System of League Client.




# Contributing
People who are interested in this project are welcome to participate in the amendment.

Currently used technologies include:

* Disassembly

Currently used tools include:

* IDA Pro7.0 x32
* uedit64

# Setup guide

* Install Digital certificate (SourceApp.cer) to  Trusted Root Certification Authorities .
* Install IDA Pro7.0
* Download the New version of League U.S. service client 
* Download the New version of League Tencent Chinese  client .

# Usage

* 　

# File 
    
	* "\SourceApp.cer"  Digital certificate file.
	* "\Game\_Specify_Ip_"                                  Specify Ip of file.
	
	   * M5D:AA88AE4E8E1761315D759F6D54D533D7
	* "\Game\BsSndRpt.exe"                                  Game deal with bug abnormal program.
	
		* M5D:0D93579AAC19781EC2EFA436458BDF1B
	* "\Game\bugsplat.dll"                                  Game deal with bug abnormal module.
	
		* M5D:0B14317CC029FC1F188C3C5872D1BCFC
	* "\Game\bugsplatrc.dll"                                Game deal with bug abnormal module (two).
	
		* M5D:9F242A01B8E44752D1A5C3E648777D2B
	* "\Game\BugTrace.dll"                                  Tencent Bug Trace Module camouflage.
	
		* M5D:559D52E634364ECB08025D3C4AB1F53F
	* "\Game\BugTrace.ini"                                  Tencent Bug Trace Module Configuration file.
	
		* M5D:EAB11D747F9A74DB28B9B6022BA5311F
	* "\Game\cg.dll"                                        NVIDIA Cg Runtime Module.
	
		* M5D:F0049C6D411969155537632F049BF016
	* "\Game\cgD3D9.dll"                                    NVIDIA Cg Runtime Module.
	
		* M5D:B1022B7ED811EE94721249134B10DBD0
	* "\Game\cgGL.dll"                                      NVIDIA Cg Runtime Module.
	
		* M5D:BBA8DB4A6A245B6E047D5B01DE1C0B68
	* "\Game\D3DCompiler_43.dll"                            DirectX Module.
	
		* M5D:6552E4B3EDD80C7909F02094B1E6AA0D
	* "\Game\d3dx9_39.dll"                                  DirectX Module.
	
		* M5D:2FBDE0B4408D47A1ECA6B9270DEE9ABC
	* "\Game\dbghelp.dll"                                   Debugging tools Module.
	
		* M5D:7286587618571245710A0DEC4B6BB6F3
	* "\Game\GameBabyConfig.dat"                            Gb Module Configuration file.
	
		* M5D:59138B718DC1A84FBDD1B6C10D1E1736
	* "\Game\GameDataPlatformServer.dll"                    Tencent Game Data Platfom Module camouflage.
	
		* M5D:905401929F98A78C09DB5CD3D47A6328
	* "\Game\GbSpy.dll"                                     Tencent Game TQMCenter Module camouflage.
	
		* M5D:C13B9A8901EBCE4C2F9D22A6FC48FACC
	* "\Game\GDPImpl.dll"                                   Tencent GDPLOL Module camouflage.
	
		* M5D:8CCFC626DDAC7AE280EFEBCBC1AECA02
	* "\Game\GDPLoader.dll"                                 Tencent GDP Loader Module camouflage.
	
		* M5D:7A58C87F3E04D7031A77292DD30F9336
	* "\Game\GDPOpenProtocol.tdr"                           Tencent GDP protocol file camouflage.
	
		* M5D:5D636882DA9BC0BBD6F4A3D0A2DFC2B0
	* "\Game\League of Legends.exe"                         Modify: League of Legends | Application.(Can read Modified WAD file) V：8.7
	
		* M5D:84EB5A75C0082D3BD8D8A155EC4232C4
	* "\Game\League_of_Legends_exe_configuration.xml"	    League of Legends exe configuration
	
		* M5D:28BEC7AF2E4453BD2B42B5C875F89B5F
	* "\Game\LogitechGkey.dll"	                            League of Legends API module. 
	
		* M5D:26A13D2D984E9C6F65418B15DA01E2C3
	* "\Game\LogitechLed.dll"	                            League of Legends API module.  
	
		* M5D:F5086BB49E7CF2907E7F0AF4B05E9E8B
	* "\Game\LOLBase.dll"	                                Tencent TP Systme Module camouflage.  
	
		* M5D:B1E86A039217BB5CED396C85E55F3E3F
	* "\Game\msvcp100.dll"                                  VC++  module.  
	
		* M5D:71D3717FC74392AC3618F65A79E27FD0
	* "\Game\msvcp110.dll"                                  VC++  module.  
	
		* M5D:823E22588135E6D3DC67BB41B2E24058
	* "\Game\msvcp120.dll"                                  VC++  module.  
	
		* M5D:A2401562CBB94FA7ABB2E8CBD48E8DE7
	* "\Game\msvcr71.dll"                                   VC++  module.  
	
		* M5D:2FAB980A98FA2381DDBFD8AE3D63DA1C
	* "\Game\msvcr100.dll"                                  VC++  module.  
	
		* M5D:006775BC025E6DC05CFD607C14FE0D00
	* "\Game\msvcr110.dll"                                  VC++  module. 
	
		* M5D:FC3CCF3F6BFE394A7414D1D7A736FF55
	* "\Game\msvcr120.dll"                                  VC++  module. 
	
		* M5D:A94F9855D86515D1672B2DEB5EA9BB85
	* "\Game\TCJ.dll"	                                    Tencent TP Systme Module camouflage.  
	
		* M5D:5D5653709EF1BBF52344BB8E2113635C
	* "\Game\TCJHelper.dll"	                                Tencent TP Systme Module Configuration file. 
	
		* M5D:1DB874E3FB904DB44CEB271B8BA8CCD4
	* "\Game\Tenparty.dat"	                                Tencent TP Systme Module Configuration file.  
	
		* M5D:5BF7A8F2399781C9ABFC3CF387E7190C
	* "\Game\TenRpcs.dll"	                                Tencent TP Systme Module camouflage.  
	
		* M5D:0BCA1D0BE603181D39999E659372D4FB
	* "\Game\TenSLX.dat"	                                Tencent TP Systme Module Configuration file.
	
		* M5D:6B2FDDC8EAE04ACD7FBA092B8206A727
	* "\Game\TenSLX.dll"	                                Tencent TP Systme Module camouflage. 
	
		* M5D:06F782F0280170D6970C0282F42C896F
	* "\Game\TenSLX2.dat"		                            Tencent TP Systme Module Configuration file.
	
		* M5D:FEC14C69F373448AB03C35796E37F25C
	* "\Game\TenSRL.dat"	                                Tencent TP Systme Module Configuration file.
	
		* M5D:AEE7DAA084DBC29E15DFC147229B637E
	* "\Game\TerSafe.dll"		
	
		* M5D:BAE943E1000D906998C0BFD6A2596A86
	* "\Game\TP3Helper.exe"	                                Tencent TP Systme EXE camouflage.  
	
		* M5D:42CDADC469D850692720C37707A6CD13
	* "\Game\util.dll"	                                    Tencent TP Systme Module camouflage.  
	
		* M5D:3542713EE374E02C4BE5BE9835161E4A
	* "\Game\"		
	* "\Game\"	




	
	
# Instructions
* Please test your own modified module to enter the game normally, and there is no problem in the game, after uploading the file.