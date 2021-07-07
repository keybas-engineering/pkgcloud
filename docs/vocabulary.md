## Unified Vocabulary

When considering all IaaS providers as a whole, their vocabulary is somewhat disjointed. `pkgcloud` attempts to overcome this through a unified vocabulary. Note that all Database providers use the same vocabulary: _database_.

### Compute

<table>
  <tr>
    <th>pkgcloud</th>
    <th>OpenStack</th>
    <th>Azure</th>
    <th>Rackspace</th>
    <th>DigitalOcean</th>
    <th>HP</th>
  </tr>
  <tr>
    <td>Server</td>
    <td>Server</td>
    <td>Instance</td>
    <td>Virtual Machine</td>
    <td>Server</td>
    <td>Droplet</td>
    <td>Server</td>
  </tr>
  <tr>
    <td>Image</td>
    <td>Image</td>
    <td>AMI</td>
    <td>Image</td>
    <td>Image</td>
    <td>Image</td>
    <td>Image</td>
  </tr>
  <tr>
    <td>Flavor</td>
    <td>Flavor</td>
    <td>InstanceType</td>
    <td>RoleSize</td>
    <td>Flavor</td>
    <td>Size</td>
    <td>Flavor</td>
  </tr>
</table>

### Storage

<table>
  <tr>
    <th>pkgcloud</th>
    <th>OpenStack</th>
    <th>Azure</th>
    <th>Rackspace</th>
  </tr>
  <tr>
    <td>Container</td>
    <td>Container</td>
    <td>Container</td>
    <td>Container</td>
  </tr>
  <tr>
    <td>File</td>
    <td>StorageObject</td>
    <td>Blob</td>
    <td>File</td>
  </tr>
</table>
