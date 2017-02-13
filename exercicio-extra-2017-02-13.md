# gcm-impacta
______________
Ultima versão do Apache:
Changes with Apache 2.4.25

  *) Fix some build issues related to various modules.
     [Rainer Jung]
____________________________________________     
 Ultima versão do TomCat
Changelog

Tomcat 9.0.0.M17 (markt)

Catalina

Add:  Extend the JreMemoryLeakPreventionListener to provide protection against ForkJoinPool.commonPool() related memory leaks. (markt)
Coyote

Fix:  Ensure UpgradeProcessor instances associated with closed connections are removed from the map of current connections to Processors. (markt)
Fix:  Remove a workaround for a problem previously reported with WebSocket, TLS and APR that treated some error conditions as not errors. The original problem cannot be reproduced with the current code and the work-around is now causing problems. (markt)
Jasper

Fix:  60497: Follow up fix using a better variable name for the tag reuse flag. (remm)
Fix:  Revert use of try/finally for simple tags. (remm)
WebSocket

Fix:  Prevent potential processing loop on unexpected WebSocket connection closure. (markt)
jdbc-pool

Add:  Enable reset the statistics without restarting the pool. (kfujino)
Other

Update:  Update the NSIS Installer used to build the Windows installer to version 3.01. (markt)
Fix:  Spelling corrections provided by Josh Soref. (violetagg)


___________________________________________
Ultima versão do Eclipse

https://eclipse.org/eclipse/news/4.7/M1/
