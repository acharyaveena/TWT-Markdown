# Tech Writing Project

- [Tech Writing Project](#tech-writing-project)
  - [Introducing the GigaVUE‑HC3 Chassis](#introducing-the-gigavuehc3-chassis)
  - [GigaVUE‑HC3 Overview](#gigavuehc3-overview)
    - [Control Card Version 1 (CCv1)](#control-card-version-1-ccv1)
      - [Table 2: Extension Board Ports and LEDs](#table-2-extension-board-ports-and-leds)
    - [Unpacking the GigaVUE‑HC3 Shipment](#unpacking-the-gigavuehc3-shipment)

## Introducing the GigaVUE‑HC3 Chassis

The fully-assembled GigaVUE‑HC3 chassis consists of a 3RU, rack-mountable, 19in-wide chassis with management, network, and tool ports at the front and power connections, fans, and access to the control card at the rear. GigaSMART is available with SMT-HC3-C05 installed in the chassis. 1Introducing the GigaVUE‑HC3 Chassis summarizes the bays on the front, including modules and extension board, and Rear View of the GigaVUE‑HC3 Chassis summarizes the rear of the GigaVUE‑HC3 chassis including fans and power supply modules.

## GigaVUE‑HC3 Overview
The GigaVUE‑HC3 node delivers the next-generation fabric visibility and security delivery platform. It offers high capacity in a modular 3RU footprint. It is optimized for 40Gb and 100Gb connectivity and offers port modules and high-performance GigaSMART.

![Image](/images/amazon.png)

### Control Card Version 1 (CCv1)
Control card version 1 (CCv1) supports the following modules:
* PRT-HC3-X24
* PRT-HC3-C08Q08
* SMT-HC3-C05
* BPS-HC3-C25F2G
* BPS-HC3-Q35C2G
* BPS-HC3-C35C2G

 
#### Table 2: Extension Board Ports and LEDs
| LED | LED Color |Description
| --- | --- | --- |
CON Port | -- | Configure the GigaVUE‑HC3 locally over a serial terminal connection (RJ-45 console port).
P/S | -- | Reserved for future use.
PPS(IN) | -- | Reserved for future use.
MGMT Port LEDs | Solid Amber <br> Blinking Green | Link Up <br> Activity
STACK Port LEDs | Solid Green <br> Solid Amber |
PWR | OFF <br> Solid Green <br> Solid Red | Power is disconnected <br> Normal operation <br> Fault
M/S | OFF <br> Solid Green | Node is member node (standby or normal node) in a cluster. Note:  When a GigaVUE‑HC3 node is a standalone node, the M/S LED could be OFF or Solid Green, depending on whether or not it was ever the leader in a cluster previously. <br> Node is a leader in a cluster.
 
### Unpacking the GigaVUE‑HC3 Shipment

The GigaVUE‑HC3 node is shipped assembled, except for the modules. The extension board is already installed in the front of the chassis. The control card, fan tray, and two power supply modules (PSMs) are already installed in the rear of the chassis. Filler panels occupy the four front module slots and two rear PSM slots.
The shipping package includes the chassis, an accessory kit containing standard cables and screws, a rack mounting rail kit, and the left and right sides of the optional cable management assembly.
The modules are shipped in separate boxes.

**Use the following procedure to unpack the node:**


1.  Inspect the shipping boxes. If any cartons were damaged, file a claim with the carrier who delivered them.

2. Open the box containing the GigaVUE‑HC3 chassis and remove the accessory kit from the top of the shipment. The accessory kit includes the power cords, console cable and adapter, and the left and right sides of the optional cable management assembly.

    If you plan on installing the optional cable management assembly, set aside the two parts.

3. Open the module boxes and set them aside.

4. Leave all protective filler panels in place in the chassis. DO NOT install the modules yet. Gigamon recommends rack-mounting the GigaVUE‑HC3 chassis without the modules because of its weight (~88lb).

<table class="table table-striped">
<caption>Caption for this Table</caption>
<thead class="thead-dark">
<tr>
    <th width="30%">Property</th>
    <th width="70%">Description</th>
    </tr>
</thead>
<tbody>
<tr>
    <td>Topic1 </td>
    <td>Topic2
        <ul>
        <li>Bullet item</li>
        <li>Bullet item</li>
        </ul>
        </td>
    </tr>
<tr>
    <td>TopicA</td>
    <td>TopicB</td>
    </tr>
</tbody>
</table>

