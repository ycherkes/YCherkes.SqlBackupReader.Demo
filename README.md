# YCherkes.SqlBackupReader.Demo
A binaries of https://github.com/ycherkes/OrcaSql with a demo version of Sql Backup Reader plugin.

The license and distribution method for the full version of this plugin and source code are not yet defined.

The demo version is obfuscated, limited only by the uncompressed backup format and will be valid until June 29, 2020.

As a result of my work, I would like to get some money and I see such ways:

  * MIT license          - $ 85,000;
  * Any copyleft license - $ 100,000;
  * Private ownership    - $ 120,000.
  
Please email me with any suggestions to ycherkes@outlook.com

What full version of plugin supports:
 * full database backups;
 * only first backup from the backup set;
 * uncompressed backups;
 * compressed backups (v1 and v2, v2 version could be optimized in future by using an additional 20 bytes of information before each compressed block of data);
 * Multiple Sql data files identification.
 
 What full version of plugin doesn't support now:
  * differantial backups;
  * more than one backup from the backup set;
  * FileStreams;
  * encrypted backups;
  * Sql log file identification;
  
Plugin features can be improved based on an additional contract.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.
