#Unity Networking

<table>
<tr>
    <th>
        Images
    </th>
    <th>
        Description
    </th>
    <th>
        code
    </th>
</tr>
  <tr>
    <td>
        <div width="350" >
            <b>Packet Class</b><br>
            <img href="https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiY2xhc3NEaWFncmFtXG5cbiAgICBjbGFzcyBQYWNrZXR7XG4gICAgICtMaXN0PGJ5dGU-IGJ1ZmZlclxuICAgICArYnl0ZVtdIHJlYWRhYmxlQnVmZmVyXG4gICAgIFBhY2tldChpbnQgX2lkKVxuICAgICBtYXRlKClcbiAgICAgV3JpdGVMZW5ndGgoKVxuICAgICBSZXNldChib29sIF9zaG91bGRSZXNldCA9IHRydWUpXG4gICAgIFdyaXRlKHN0cmluZyBfbXNnKVxuICAgIH1cblxuICAgICAgICAgICAgIiwibWVybWFpZCI6e30sInVwZGF0ZUVkaXRvciI6ZmFsc2V9" src="https://mermaid.ink/img/eyJjb2RlIjoiY2xhc3NEaWFncmFtXG5cbiAgICBjbGFzcyBQYWNrZXR7XG4gICAgICtMaXN0PGJ5dGU-IGJ1ZmZlclxuICAgICArYnl0ZVtdIHJlYWRhYmxlQnVmZmVyXG4gICAgIFBhY2tldChpbnQgX2lkKVxuICAgICBtYXRlKClcbiAgICAgV3JpdGVMZW5ndGgoKVxuICAgICBSZXNldChib29sIF9zaG91bGRSZXNldCA9IHRydWUpXG4gICAgIFdyaXRlKHN0cmluZyBfbXNnKVxuICAgIH1cblxuICAgICAgICAgICAgIiwibWVybWFpZCI6e30sInVwZGF0ZUVkaXRvciI6ZmFsc2V9" width="950"/> 
        </div>
    </td>
    <td> 
        <div width="450">
            Use to serialise and deserialise the packet bytes into datatype 
        </div>
    </td>
    <td> 
        <div markdown=1>
         Code For sending the data

```csharp
using (Packet _packet = new Packet((int)ServerPackets.welcome))
{
_packet.Write(_msg);
_packet.Write(_toClient);

SendTCPData(_toClient, _packet);
}
```

</div>
 </td>
</tr> 

<tr>
    <th>
        Images
    </th>
    <th>
        Description
    </th>
    <th>
        code
    </th>
</tr>
  <tr>
    <td>
        <div width="350" >
            <b>Packet Class</b><br>
            <img href="https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiY2xhc3NEaWFncmFtXG5cbiAgICBjbGFzcyBQYWNrZXR7XG4gICAgICtMaXN0PGJ5dGU-IGJ1ZmZlclxuICAgICArYnl0ZVtdIHJlYWRhYmxlQnVmZmVyXG4gICAgIFBhY2tldChpbnQgX2lkKVxuICAgICBtYXRlKClcbiAgICAgV3JpdGVMZW5ndGgoKVxuICAgICBSZXNldChib29sIF9zaG91bGRSZXNldCA9IHRydWUpXG4gICAgIFdyaXRlKHN0cmluZyBfbXNnKVxuICAgIH1cblxuICAgICAgICAgICAgIiwibWVybWFpZCI6e30sInVwZGF0ZUVkaXRvciI6ZmFsc2V9" src="https://mermaid.ink/img/eyJjb2RlIjoiY2xhc3NEaWFncmFtXG5cbiAgICBjbGFzcyBQYWNrZXR7XG4gICAgICtMaXN0PGJ5dGU-IGJ1ZmZlclxuICAgICArYnl0ZVtdIHJlYWRhYmxlQnVmZmVyXG4gICAgIFBhY2tldChpbnQgX2lkKVxuICAgICBtYXRlKClcbiAgICAgV3JpdGVMZW5ndGgoKVxuICAgICBSZXNldChib29sIF9zaG91bGRSZXNldCA9IHRydWUpXG4gICAgIFdyaXRlKHN0cmluZyBfbXNnKVxuICAgIH1cblxuICAgICAgICAgICAgIiwibWVybWFpZCI6e30sInVwZGF0ZUVkaXRvciI6ZmFsc2V9" width="950"/> 
        </div>
    </td>
    <td> 
        <div width="450">
            Use to serialise and deserialise the packet bytes into datatype 
        </div>
    </td>
    <td> 
        <div markdown=1>
         Code For sending the data

```csharp
using (Packet _packet = new Packet((int)ServerPackets.welcome))
{
_packet.Write(_msg);
_packet.Write(_toClient);

SendTCPData(_toClient, _packet);
}
```

</div>
 </td>
</tr> 
   
</table>
