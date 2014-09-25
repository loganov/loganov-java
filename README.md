loganov-java Cookbook
=====================
Wrapper for OpsCode Java cookbook. 

Requirements
------------
#### packages
- `java` - requires OpsCode java cookbook

Attributes
----------
#### loganov-java::default
<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['java']['jdk_version']</tt></td>
    <td>String</td>
    <td>JavaSE version</td>
    <td><tt>7</tt></td>
  </tr>
  <tr>
    <td><tt>['java']['arch']</tt></td>
    <td>String</td>
    <td>Platform</td>
    <td><tt>x86_64</tt></td>
  </tr>
  <tr>
    <td><tt>['java']['accept_license_agreement']</tt></td>
    <td>Boolean</td>
    <td>Accept license agreement</td>
    <td><tt>true</tt></td>
  </tr>
  <tr>
    <td><tt>['java']['install_flavor']</tt></td>
    <td>String</td>
    <td>OpenJDK, or Oracle</td>
    <td><tt>oracle</tt></td>
  </tr>
  <tr>
    <td><tt>['java']['oracle']['accept_oracle_download_terms']</tt></td>
    <td>Boolean</td>
    <td>Accept Oracle license agreement</td>
    <td><tt>true</tt></td>
  </tr>
  <tr>
    <td><tt>['java']['jdk']['7']['x86_64']['url'] </tt></td>
    <td>String</td>
    <td>URL for JDK</td>
    <td><tt>http://download.oracle.com/otn-pub/java/jdk/7u51-b13/jdk-7u51-linux-x64.tar.gz</tt></td>
  </tr>
  <tr>
    <td><tt>['java']['jdk']['7']['x86_64']['checksum']</tt></td>
    <td>String</td>
    <td>Checksum for JDK</td>
    <td><tt>764f96c4b078b80adaa5983e75470ff2</tt></td>
  </tr>
  <tr>
    <td><tt>['loganov']['java']['home']</tt></td>
    <td>String</td>
    <td>Java home softlink.</td>
    <td><tt>/usr/java/latest</tt></td>
  </tr>
</table>

Usage
-----
#### loganov-java::default
TODO: Write usage instructions for each cookbook.

e.g.
Just include `loganov-java` in your node's `run_list` and override the appropriate attributes in `default.rb`.

License and Authors
-------------------
Authors: Gregory Weaver
