# Launch an instance

## Instance details

ข้อมูลที่ใช้ในการสร้าง **Instance** ควรทำความเข้าใจถึงข้อมูลต่างๆที่ใช้ในการสร้าง Instance ก่อน ดังนี้

<table>
  <thead>
    <tr>
      <th style="text-align:left"><b>Detail</b>
      </th>
      <th style="text-align:left"><b>Description</b>
      </th>
      <th style="text-align:center">Optional</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Hostname</b>
      </td>
      <td style="text-align:left">&#xE0A;&#xE37;&#xE48;&#xE2D; instance</td>
      <td style="text-align:center">no</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Image</b>
      </td>
      <td style="text-align:left">&#xE23;&#xE30;&#xE1A;&#xE1A;&#xE1B;&#xE0F;&#xE34;&#xE1A;&#xE31;&#xE15;&#xE34;&#xE01;&#xE32;&#xE23;
        (Operating System) &#xE02;&#xE2D;&#xE07; Instance</td>
      <td style="text-align:center">no</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Machine Type</b>
      </td>
      <td style="text-align:left">Specification &#xE02;&#xE2D;&#xE07; Instance (&#xE41;&#xE15;&#xE48;&#xE25;&#xE30;&#xE1B;&#xE23;&#xE30;&#xE40;&#xE20;&#xE17;&#xE21;&#xE35;&#xE08;&#xE33;&#xE19;&#xE27;&#xE19;&#xE08;&#xE33;&#xE01;&#xE31;&#xE14;
        &#xE2B;&#xE32;&#xE01; spec &#xE44;&#xE2B;&#xE19;&#xE40;&#xE2B;&#xE25;&#xE37;&#xE2D;&#xE19;&#xE49;&#xE2D;&#xE22;&#xE01;&#xE27;&#xE48;&#xE32;
        10 &#xE40;&#xE04;&#xE23;&#xE37;&#xE48;&#xE2D;&#xE07; &#xE08;&#xE30;&#xE41;&#xE2A;&#xE14;&#xE07;&#xE08;&#xE33;&#xE19;&#xE27;&#xE19;&#xE40;&#xE04;&#xE23;&#xE37;&#xE48;&#xE2D;&#xE07;&#xE17;&#xE35;&#xE48;&#xE40;&#xE2B;&#xE25;&#xE37;&#xE2D;&#xE44;&#xE27;&#xE49;
        &#xE41;&#xE25;&#xE30;&#xE1B;&#xE23;&#xE30;&#xE40;&#xE20;&#xE17;&#xE44;&#xE2B;&#xE19;&#xE17;&#xE35;&#xE48;&#xE2B;&#xE21;&#xE14;
        &#xE08;&#xE30;&#xE41;&#xE2A;&#xE14;&#xE07;&#xE02;&#xE49;&#xE2D;&#xE04;&#xE27;&#xE32;&#xE21;
        out of stock)</td>
      <td style="text-align:center">no</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Cloud Firewall</b>
      </td>
      <td style="text-align:left">
        <p>&#xE2A;&#xE48;&#xE27;&#xE19;&#xE17;&#xE35;&#xE48;&#xE23;&#xE30;&#xE1A;&#xE38;&#xE01;&#xE32;&#xE23;&#xE40;&#xE02;&#xE49;&#xE32;&#xE16;&#xE36;&#xE07;
          Instance &#xE42;&#xE14;&#xE22;&#xE23;&#xE30;&#xE1A;&#xE1A;&#xE08;&#xE30;&#xE21;&#xE35;
          Default Cloud Firewall &#xE43;&#xE2B;&#xE49; &#xE14;&#xE31;&#xE07;&#xE19;&#xE35;&#xE49;</p>
        <ul>
          <li>All</li>
          <li>Rdp</li>
          <li>Http-Https</li>
          <li>default</li>
          <li>In-Cluster</li>
          <li>Ping</li>
          <li>SSH</li>
        </ul>
        <p>&#xE1C;&#xE39;&#xE49;&#xE43;&#xE0A;&#xE49;&#xE07;&#xE32;&#xE19;&#xE2A;&#xE32;&#xE21;&#xE32;&#xE23;&#xE16;&#xE2A;&#xE23;&#xE49;&#xE32;&#xE07;
          Cloud Firewall &#xE40;&#xE1E;&#xE34;&#xE48;&#xE21;&#xE40;&#xE15;&#xE34;&#xE21;&#xE44;&#xE14;&#xE49;
          &#xE42;&#xE14;&#xE22;&#xE14;&#xE39;&#xE08;&#xE32;&#xE01;&#xE2B;&#xE31;&#xE27;&#xE02;&#xE49;&#xE2D;
          Create Cloud Firewall</p>
      </td>
      <td style="text-align:center">no</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Authentication</b>
      </td>
      <td style="text-align:left">&#xE2A;&#xE48;&#xE27;&#xE19;&#xE17;&#xE35;&#xE48;&#xE01;&#xE33;&#xE2B;&#xE19;&#xE14;
        keypair &#xE2B;&#xE23;&#xE37;&#xE2D; password &#xE43;&#xE19;&#xE01;&#xE32;&#xE23;&#xE40;&#xE02;&#xE49;&#xE32;&#xE43;&#xE0A;&#xE49;&#xE07;&#xE32;&#xE19;
        &#xE42;&#xE14;&#xE22; keypair &#xE1C;&#xE39;&#xE49;&#xE43;&#xE0A;&#xE49;&#xE07;&#xE32;&#xE19;&#xE2A;&#xE23;&#xE49;&#xE32;&#xE07;&#xE40;&#xE1E;&#xE34;&#xE48;&#xE21;&#xE40;&#xE15;&#xE34;&#xE21;&#xE44;&#xE14;&#xE49;
        &#xE42;&#xE14;&#xE22;&#xE14;&#xE39;&#xE08;&#xE32;&#xE01;&#xE2B;&#xE31;&#xE27;&#xE02;&#xE49;&#xE2D;
        create keypair</td>
      <td style="text-align:center">no</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Number of Instances</b>
      </td>
      <td style="text-align:left">&#xE08;&#xE33;&#xE19;&#xE27;&#xE19; instance &#xE17;&#xE35;&#xE48;&#xE15;&#xE49;&#xE2D;&#xE07;&#xE01;&#xE32;&#xE23;&#xE2A;&#xE23;&#xE49;&#xE32;&#xE07;</td>
      <td
      style="text-align:center">no</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Instance Volume</b>
      </td>
      <td style="text-align:left">&#xE02;&#xE19;&#xE32;&#xE14;&#xE02;&#xE2D;&#xE07; volume (&#xE2A;&#xE32;&#xE21;&#xE32;&#xE16;&#xE23;&#xE30;&#xE1A;&#xE38;&#xE44;&#xE14;&#xE49;&#xE43;&#xE19;&#xE01;&#xE23;&#xE13;&#xE35;&#xE17;&#xE35;&#xE48;&#xE40;&#xE25;&#xE37;&#xE2D;&#xE01;
        image &#xE41;&#xE1A;&#xE1A; Distributions, Marketplace &#xE2B;&#xE23;&#xE37;&#xE2D;
        Images &#xE41;&#xE25;&#xE30;&#xE2A;&#xE23;&#xE49;&#xE32;&#xE07;&#xE41;&#xE1A;&#xE1A;
        boot volume)</td>
      <td style="text-align:center">yes</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Network</b>
      </td>
      <td style="text-align:left">&#xE2A;&#xE48;&#xE27;&#xE19;&#xE17;&#xE35;&#xE48;&#xE01;&#xE33;&#xE2B;&#xE19;&#xE14;
        network &#xE17;&#xE35;&#xE48;&#xE15;&#xE49;&#xE2D;&#xE07;&#xE01;&#xE32;&#xE23;&#xE43;&#xE0A;&#xE49;&#xE07;&#xE32;&#xE19;
        &#xE42;&#xE14;&#xE22;&#xE2A;&#xE32;&#xE21;&#xE32;&#xE23;&#xE16;&#xE01;&#xE33;&#xE2B;&#xE19;&#xE14;
        IP Address &#xE17;&#xE35;&#xE48;&#xE15;&#xE49;&#xE2D;&#xE07;&#xE01;&#xE32;&#xE23;&#xE43;&#xE0A;&#xE49;&#xE07;&#xE32;&#xE19;&#xE44;&#xE14;&#xE49;</td>
      <td
      style="text-align:center">yes</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>External IP</b>
      </td>
      <td style="text-align:left">&#xE2A;&#xE48;&#xE27;&#xE19;&#xE17;&#xE35;&#xE48;&#xE01;&#xE33;&#xE2B;&#xE19;&#xE14;
        IP Address &#xE17;&#xE35;&#xE48;&#xE43;&#xE0A;&#xE49;&#xE43;&#xE19;&#xE01;&#xE32;&#xE23;&#xE40;&#xE0A;&#xE37;&#xE48;&#xE2D;&#xE21;&#xE15;&#xE48;&#xE2D;
        instance &#xE01;&#xE31;&#xE1A; network &#xE20;&#xE32;&#xE22;&#xE19;&#xE2D;&#xE01;</td>
      <td
      style="text-align:center">no</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Auto Backup</b>
      </td>
      <td style="text-align:left">&#xE2A;&#xE48;&#xE27;&#xE19;&#xE17;&#xE35;&#xE48;&#xE01;&#xE33;&#xE2B;&#xE19;&#xE14;&#xE16;&#xE36;&#xE07;&#xE01;&#xE32;&#xE23;&#xE43;&#xE2B;&#xE49;&#xE23;&#xE30;&#xE1A;&#xE1A;&#xE08;&#xE31;&#xE14;&#xE01;&#xE32;&#xE23;&#xE40;&#xE01;&#xE47;&#xE1A;&#xE02;&#xE49;&#xE2D;&#xE21;&#xE39;&#xE25;
        backup instance &#xE42;&#xE14;&#xE22;&#xE2D;&#xE31;&#xE15;&#xE42;&#xE19;&#xE21;&#xE31;&#xE15;&#xE34;</td>
      <td
      style="text-align:center">no</td>
    </tr>
  </tbody>
</table>> _ส่วนที่เป็น optional \(yes/no\) ผู้ใช้งานสามารถ request ขอทาง Administrator เพื่อใช้งานเพิ่มเติมได้_

## Create an instance

### Hostname

กรอก Hostname \(ชื่อ Instance\) ที่ต้องการ \(ภายในช่องกรอกระบบจะมีชื่อ default ให้ โดยทางผู้ใช้งานสามารถตั้งชื่อใหม่ได้\)

![ ](../.gitbook/assets/1.png)

### Image

เลือก Image ที่ต้องการสร้าง โดย image จะประกอบไปด้วย 4 ประภท ดังนี้

{% tabs %}
{% tab title="Distributions" %}
> Image พื้นฐานหลักของระบบ เช่น Ubuntu, Windows, Centos เป็นต้น

![](../.gitbook/assets/2.png)
{% endtab %}

{% tab title="Marketplace" %}
> _Image ที่มี template สำเร็จรูป โดยเมื่อผู้ใช้งานสร้างด้วย image ประเภทนี้ จะสามารถนำไปใช้งานได้เลย ไม่ต้องตั้งค่าใดๆเพิ่มเติม เช่น Docker, GitLab, Wordpress เป็นต้น_

![](../.gitbook/assets/3.png)
{% endtab %}

{% tab title="Images" %}
> Image ที่เกิดจากการ snapshot ของ instance ด้วยผู้ใช้งานเอง หรือการทำ auto backup ของระบบ

![](../.gitbook/assets/4.png)
{% endtab %}

{% tab title="Volumes \(Optional\)" %}
> Image ที่เกิดจากการสร้าง volume แบบ boot volume โดยในส่วนนี้ หากผู้ใช้งานต้องใช้ feature นี้ จะต้อง request ขอมายัง Administrator เพิ่มเปิดใช้งาน

![](../.gitbook/assets/5.png)
{% endtab %}
{% endtabs %}

### **Machine Type**

เลือก Machine Type โดย Machine Type จะแสดงตามการเลือกของ image ซึ่งถูกแบ่งประเภทตามขนาดการใช้งาน ดังนี้

{% tabs %}
{% tab title="General" %}
> เป็น spec การใช้งานมาตรฐานของผู้ใช้งาน

![](../.gitbook/assets/6.png)
{% endtab %}

{% tab title="High Memory" %}
> เป็น spec ที่เหมาะกับผู้ใช้งานที่เน้นการใช้งาน memory เป็นหลัก

![](../.gitbook/assets/7.png)
{% endtab %}
{% endtabs %}

สำหรับผู้ใช้งานที่เลือกประเภท image แบบ **Boot volume** ในส่วน Disk ของ machine type จะแสดงข้อความ **"Use existing volume"** ซึ่งหมายความว่า ขนาด Disk ของ Image ประเภทนี้จะขึ้นอยู่กับจำนวนของขนาด volume image ที่เลือก

![](../.gitbook/assets/8-1.png)

### **Cloud firewall**

![](../.gitbook/assets/9-1.png)

### **Authentication**

เลือกประเภทการ Authentication ในการใช้งาน instance ซึ่งจะแสดงตามการเลือกของ image โดย Keypiar \(จะแสดงเมื่อเลือก image ประเภท linux\) และ password \(จะแสดงเมื่อเลือก image ประเภท linux หรือ windows\)

#### Keypair

![](../.gitbook/assets/10.png)

#### Password

![](../.gitbook/assets/11.png)

{% hint style="info" %}
คลิก Network, Volume and more เพื่อดูหัวข้ออื่นๆ  
{% endhint %}

![](../.gitbook/assets/12.png)

### Number of instances

เลือกจำนวน instance ที่ต้องการสร้าง โดยสามารถได้สูงสุดครั้งละ 5 instance หากเหลือ quota ในการสร้าง instance เหลือน้อยกว่า 5 จะแสดงตามจำนวน quota ที่เหลือ และสามาถสร้างได้เพียงครั้งละ 1 instance เมื่อมีการเลือก/กำหนด resource ดังนี้

* เลือก image ประเภท volume
* [Disable auto assign IP](launch-instance.md#network)
* [เลือก IP Address \(Port\) ที่ผู้ใช้งานสร้างขึ้นเอง](launch-instance.md#network)
* [เลือก External IP ที่ผู้ใช้งานสร้างขึ้นเอง](launch-instance.md#external-ip)

![](../.gitbook/assets/13.png)

### **Instance Volume**

กำหนดขนาดของ **Disk** เมื่อสร้าง I**nstance** แบบ **Boot volume** โดยจะสามารถกำหนดได้เมื่อเลือก image ประเภท Distributions, Marketplace หรือ Images เท่านั้น หากเลือก image ประเภท volume จะใช้ขนาดตาม volume ที่เลือก __\(Optional\)

![](../.gitbook/assets/14.png)

### **Network**

เลือก **Network** ที่ต้องการสร้าง instance หากผู้ใช้งานเลือก network แบบ Public จะไม่สามารถเลือก [External IP](launch-instance.md#external-ip) ได้ นอกจากกำหนด network แล้วผู้ใช้งานสามารถกำหนด IP Address \(หมายเลข port\) ของ instance หรือสร้าง port \(ดูได้จากหัวข้อ Create Port\) ได้ด้วยตนเอง หากหมายเลขนั้นไม่มีผู้ใช้งานคนอื่นๆใช้งานอยู่ _**\(Optional\)**_

![&#xE40;&#xE25;&#xE37;&#xE2D;&#xE01; default network &#xE41;&#xE25;&#xE30; Auto Assign IP](../.gitbook/assets/15.png)

![&#xE40;&#xE25;&#xE37;&#xE2D;&#xE01; default network &#xE41;&#xE25;&#xE30; port &#xE17;&#xE35;&#xE48;&#xE1C;&#xE39;&#xE49;&#xE43;&#xE0A;&#xE49;&#xE07;&#xE32;&#xE19;&#xE2A;&#xE23;&#xE49;&#xE32;&#xE07;&#xE40;&#xE2D;&#xE07;](../.gitbook/assets/16.png)

![&#xE40;&#xE25;&#xE37;&#xE2D;&#xE01; default network &#xE41;&#xE25;&#xE30; &#xE01;&#xE33;&#xE2B;&#xE19;&#xE14; IP Address &#xE17;&#xE35;&#xE48;&#xE1C;&#xE39;&#xE49;&#xE43;&#xE0A;&#xE49;&#xE07;&#xE32;&#xE19;&#xE15;&#xE49;&#xE2D;&#xE07;&#xE01;&#xE32;&#xE23;](../.gitbook/assets/17.png)

### **External IP**

* **Create a new IP:** ระบบจะทำการสุ่ม External IP ที่ไม่ถูกใช้งานให้  
* **Disabled:** Instance ที่ถูกสร้างจะไม่มีการใช้งาน External IP  
* เลือก External IP ที่ผู้ใช้งานสร้างเอง \(ดูได้จากหัวข้อ Create External IPs\)  
* Enable **Bypass internal network:** instance ที่ถูกสร้างจะได้ internal IP เป็นเลข External IP แทน หาก Enable จะไม่สามารถเลือก [Network](launch-instance.md#network) ได้

![&#xE40;&#xE25;&#xE37;&#xE2D;&#xE01; Create a new IP](../.gitbook/assets/18.png)

![&#xE40;&#xE25;&#xE37;&#xE2D;&#xE01; Disabled](../.gitbook/assets/19.png)

![&#xE40;&#xE25;&#xE37;&#xE2D;&#xE01; External IP &#xE17;&#xE35;&#xE48;&#xE1C;&#xE39;&#xE49;&#xE43;&#xE0A;&#xE49;&#xE07;&#xE32;&#xE19;&#xE2A;&#xE23;&#xE49;&#xE32;&#xE07;&#xE40;&#xE2D;&#xE07;](../.gitbook/assets/20.png)

![Enable Bypass internal network](../.gitbook/assets/21.png)

### **Auto Backup**

* **Enabled:** ระบบจะทำการ backup instance 2 files ทุกๆ 7 วัน ตอน 03:00 น. ให้อัตโนมัติ
* **Disabled:** ระบบจะไม่ทำการ backup instance ให้ ซึ่งผู้ใช้งานจะต้องทำการ backup instance ด้วยตนเอง โดยการ snapshot

![](../.gitbook/assets/22-1.png)

คลิกปุ่ม Create เพื่อสร้าง instance โดยทางด้านซ้ายของปุ่ม จะแสดงราคาต่อเดือนตาม resource ที่ผู้ใช้งานเลือก

![](../.gitbook/assets/23.png)

### **Instance list**

เมื่อคลิกสร้าง Instance แล้ว ระบบจะแสดงหน้า instance list หากสร้างสำเร็จจะแสดงผลลัพธ์ตามรูปด้านล่าง

![&#xE40;&#xE25;&#xE37;&#xE2D;&#xE01; Network: Default / External IP: Create a new IP](../.gitbook/assets/24.png)

![&#xE40;&#xE25;&#xE37;&#xE2D;&#xE01; Network: Default / External IP: Disabled](../.gitbook/assets/25-1.png)

![&#xE40;&#xE25;&#xE37;&#xE2D;&#xE01; External IP: Bypass internal netowrk ](../.gitbook/assets/26.png)

หากสร้าง Instance แบบ Boot volume จะไม่สามารถดูผลลัพธ์ได้ในหน้า Instance list ผู้ใช้งานจะสามารถตรวจสอบได้ที่ Instance detail โดยคลิกที่ชื่อ Instance

![](../.gitbook/assets/27.png)

โดยภายใน Instance detail จะแสดงข้อมูลขนาด Disk ของ Instance เป็นประเภท Volume และมี 1 Volume หลังจากสร้าง Instance เรียบร้อยแล้ว

![](../.gitbook/assets/28.png)
