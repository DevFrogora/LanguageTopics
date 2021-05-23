#Unity Networking

<table>
<tr>
    <td>
        Images
    </td>
    <td>
        Description
    </td>
    <td>
        code
    </td>
</tr>
  <tr>
    <td>
        <div width="350" >
            <b>WindowFrame</b><br>
            <img href="https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiY2xhc3NEaWFncmFtXG5cbiAgICBjbGFzcyBQYWNrZXR7XG4gICAgICtMaXN0PGJ5dGU-IGJ1ZmZlclxuICAgICArYnl0ZVtdIHJlYWRhYmxlQnVmZmVyXG4gICAgIFBhY2tldChpbnQgX2lkKVxuICAgICBtYXRlKClcbiAgICAgV3JpdGVMZW5ndGgoKVxuICAgICBSZXNldChib29sIF9zaG91bGRSZXNldCA9IHRydWUpXG4gICAgIFdyaXRlKHN0cmluZyBfbXNnKVxuICAgIH1cblxuICAgICAgICAgICAgIiwibWVybWFpZCI6e30sInVwZGF0ZUVkaXRvciI6ZmFsc2V9" src="https://mermaid.ink/img/eyJjb2RlIjoiY2xhc3NEaWFncmFtXG5cbiAgICBjbGFzcyBQYWNrZXR7XG4gICAgICtMaXN0PGJ5dGU-IGJ1ZmZlclxuICAgICArYnl0ZVtdIHJlYWRhYmxlQnVmZmVyXG4gICAgIFBhY2tldChpbnQgX2lkKVxuICAgICBtYXRlKClcbiAgICAgV3JpdGVMZW5ndGgoKVxuICAgICBSZXNldChib29sIF9zaG91bGRSZXNldCA9IHRydWUpXG4gICAgIFdyaXRlKHN0cmluZyBfbXNnKVxuICAgIH1cblxuICAgICAgICAgICAgIiwibWVybWFpZCI6e30sInVwZGF0ZUVkaXRvciI6ZmFsc2V9" width="650"/> 
        </div>
    </td>
    <td> 
        <div>
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
