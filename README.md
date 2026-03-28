# <p align="center">ServiceNow Homelab</p>

<p align="center">A personal developer instance configured to demonstrate core ITSM workflows including incident management, request fulfilment, assignment rules, and reporting. Built using a free ServiceNow Personal Developer Instance (PDI).</p>

---

## <p align="center">Environment Setup</p>

### <p align="center">Created Dev Account and Requested PDI</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483540445593210890/image.png?ex=69c8cdf5&is=69c77c75&hm=d94afc23a715371c1f352464c875fd4ee09ed1685c93bacd8363510a7a5894e4&" alt="Created Dev Account and Requested PDI" width="800"/>
</p>

<p align="center">Registered at developer.servicenow.com and provisioned a Personal Developer Instance.</p>

---

## <p align="center">User and Group Creation</p>

### <p align="center">Creating Some Users to Simulate a Real Team</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483543854551666788/image.png?ex=69c8d121&is=69c77fa1&hm=5a506e7c278c8a9bb746490aba9ed02884e3a9699ea3838ca095fb62e37c1995&" alt="Creating users" width="800"/>
</p>
<p align="center">

  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483544241262039041/image.png?ex=69c8d17e&is=69c77ffe&hm=17a688ea2cf05549d51b49cc4ccd12613d4b5761f8f64dbec115890045ee69a8&"  width="800"/>

</p>
<p align="center">

  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483544574411538452/image.png?ex=69c8d1cd&is=69c7804d&hm=6424454ab61505327d9654401205cadc18af6319268057789f86fe62a19d0014&"  width="800"/>

</p>

<p align="center">Created multiple user accounts representing L1 agents, L2 engineers, end users and a manager.</p>

### <p align="center">Creating Groups to Assign New Users To</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483545252177645692/image.png?ex=69c8d26f&is=69c780ef&hm=64522896c6539f91501c7c0b4d3097ebfe522a61d7ca0a6101c75554c68bc8bb&" alt="Creating groups" width="800"/>
</p>
<p align="center">

  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483545425863639091/image.png?ex=69c8d298&is=69c78118&hm=30763b19040830c323752f50e4ed45fc143f5701bcdc01f7c93b87bba7281303&"  width="800"/>

</p>
<p align="center">

  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483546253286576308/image.png?ex=69c8d35d&is=69c781dd&hm=5371e2e6e027dbd0fcfdc924d0bcb217bfb7c27630294e296ee8082e91130d08&"  width="800"/>

</p>

<p align="center">Configured Relevant groups under User Administration.</p>

### <p align="center">Assigning Users to Groups</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483547070613946419/image.png?ex=69c8d420&is=69c782a0&hm=bdbbcd117534f5ccafad4e54a894e4ae0a1b8d14a2c69e291304916c7de3c79d&" alt="Assigning users to groups" width="800"/>
</p>

<p align="center">

  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483550878215704626/image.png?ex=69c8d7ac&is=69c7862c&hm=556a79fa456be1c46f748d93ca087be2d0cf2ad4370661c39a0957f57ffbaf1b&"  width="800"/>

</p>

<p align="center">

  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483551435714199612/image.png?ex=69c8d831&is=69c786b1&hm=b5224fec60cc2457745fbf762223e6b23d8092f9e8a90577c5a653414549def7&"  width="800"/>

</p>
<p align="center">

  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483549949814898718/image.png?ex=69c8d6cf&is=69c7854f&hm=c07431cd71c5c3aad57b222c474ad71711f886f4f38ce9ed2dc652f83fbbfc17&"  width="800"/>

</p>


<p align="center">Users assigned to appropriate groups via the Group Members tab.</p>


---

## <p align="center">Assignment Rules</p>

### <p align="center">Sample Assignment Rule — Hardware Incidents to L1</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483553143714222090/image.png?ex=69c8d9c8&is=69c78848&hm=785b3491c4d4110181f4dd4ab9bb51ca51e5b16a3faa363d50c219ece9ae13f3&" alt="Hardware assignment rule" width="800"/>
</p>

<p align="center">

  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483553208914677923/image.png?ex=69c8d9d8&is=69c78858&hm=b226d2318f82f3aae521c44053e3774c4b6e3a58945804f1da8e43dc2ed9cf55&"  width="800"/>

</p>

<p align="center">Assignment Lookup Rule routing Category = Hardware incidents to IT Helpdesk L1.</p>

### <p align="center">Database Incidents to L2</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483553923137802482/image.png?ex=69c8da82&is=69c78902&hm=dc90eec8ede7b0669740c85a4f92896b2555c34eccd91af647ff0ef1507eaf49&" alt="Database assignment rule" width="800"/>
</p>
<p align="center">

  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483553955119104182/image.png?ex=69c8da8a&is=69c7890a&hm=99594d3e1ff51c8710881601379020bd4560a90b3170fab3b934d6c164d3c32c&"  width="800"/>

</p>


<p align="center">Higher priority rule routing Database incidents directly to IT Helpdesk L2, bypassing L1.</p>

### <p align="center">Sample Hardware Incident Test</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483556811683528744/image.png?ex=69c8dd33&is=69c78bb3&hm=379017cb3a9e9c9f98fae6ccf960ff58c93a2ba7d61b6bc57e91411bc790692b&" alt="Sample hardware incident" width="800"/>
</p>

<p align="center">Sample hardware incident raised via the Service Portal.</p>

### <p align="center">The Incident Has Been Auto Assigned to L1</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483557020933029898/image.png?ex=69c8dd64&is=69c78be4&hm=7ed334a4c9a12e9fd84e535b86138bb7276a42b827eb012741febc35ca1d2d53&" alt="Auto assigned to L1" width="800"/>
</p>

<p align="center">Incident auto-assigned to IT Helpdesk L1 on creation, confirming the assignment rule is working.</p>

### <p align="center">Test for Database Rule</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483557323627827390/image.png?ex=69c8ddad&is=69c78c2d&hm=fa93804fb662d7b962b8dba0379f877d6cd23283c4bf4c5cdd3955d368b977e2&" alt="Database rule test" width="800"/>
</p>

<p align="center">

  <img src="https://media.discordapp.net/attachments/1483540272167129129/1483557387418996908/image.png?ex=69c8ddbc&is=69c78c3c&hm=d2172e59a17e3b5f1db9a9ed649e621b9d410a77c54beb3fd9de3dbdc1966750&=&format=webp&quality=lossless&width=854&height=35"  width="800"/>

</p>

<p align="center">Database category incident correctly routed to IT Helpdesk L2, bypassing L1.</p>

---

## <p align="center">Sample Workflows</p>

### <p align="center">Impersonating User to Create a Request</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483585192982741094/image.png?ex=69c84ee1&is=69c6fd61&hm=f9841e9bd5348034c05f89dd7fe9eabd83a4665f7dedea71ca23348c371b1c69&" alt="Impersonating user" width="800"/>
</p>

<p align="center">

  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483585660173680688/image.png?ex=69c84f51&is=69c6fdd1&hm=14776c102991ef15e952721c71c44fc93c8573f51e324c24a2c555679149fa97&"  width="800"/>

</p>

<p align="center">Used the Impersonate User feature to simulate an end user raising two tickets via the Service Portal.</p>

### <p align="center">Assigned to L1</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483587348317864016/image.png?ex=69c850e3&is=69c6ff63&hm=ff287d2cfc712ca405db73730312dc17af401ebb659ec6ad60934229ea544331&" alt="Assigned to L1" width="800"/>
</p>
<p align="center">

  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1483587450482982952/image.png?ex=69c850fb&is=69c6ff7b&hm=34f022620251c83be27dd5bd6675c8a5ba2c35c72a05af0666a7d451ca24808f&"  width="800"/>

</p>


<p align="center">Ticket assigned to IT Helpdesk L1 group as admin.</p>

### <p align="center">Giving Helpdesk Role ITIL Permission</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1487388148005732433/image.png?ex=69c8f5a8&is=69c7a428&hm=573ee84ad7fe93873309134303530579fcb6c666783b83ac5f68704fc74f74f6&" alt="ITIL role assignment" width="800"/>
</p>

<p align="center">ITIL role assigned to the Helpdesk group to grant agents access to the incident module.</p>

### <p align="center">"My Groups Work" — Finding L1 Assigned Tasks</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1487389629207285901/image.png?ex=69c8f709&is=69c7a589&hm=199bddb6e35c38982d5aa3fb56f52363a15d486adf900a4d81332af2c836c8cf&" alt="My Groups Work" width="800"/>
</p>

<p align="center">Impersonating an L1 agent and using My Groups Work to view all tickets in the L1 queue.</p>

### <p align="center">Work Notes — Monitor Issue</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1487391695502049390/image.png?ex=69c8f8f6&is=69c7a776&hm=b8a747dec64ed67d28dd82430568d0200788b465c6760f7026b1f16d6a9f16d4&" alt="Work notes monitor" width="800"/>
</p>

<p align="center">Work notes documenting L1 troubleshooting steps for the monitor not turning on incident.</p>

### <p align="center">Resolution Notes — Monitor Issue</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1487392247325397202/image.png?ex=69c8f97a&is=69c7a7fa&hm=8636fc55a2aab03b5cf3ad502f4af2763a30c2f1f23f7bd444b04cdd4e88f4ec&" alt="Resolution notes monitor" width="800"/>
</p>

<p align="center">Resolution notes confirming HDMI cable reseated and issue resolved, confirmed by user.</p>

### <p align="center">Work Notes — Printer Issue</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1487393209335414875/image.png?ex=69c8fa5f&is=69c7a8df&hm=90f1027ebde998f5a96c2cf2c1c5034c0d87692917a3200b0f97179c2c57aa6a&" alt="Work notes printer" width="800"/>
</p>

<p align="center">Work notes for the 2nd floor printer offline incident.</p>

### <p align="center">Resolution Notes — Printer Issue</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1487393910123790367/image.png?ex=69c8fb06&is=69c7a986&hm=a9deccbe39409b8b1f479c864e3210df0d30b13101ee8a67b84b8bcb5742abd4&" alt="Resolution notes printer" width="800"/>
</p>

<p align="center">Resolution notes confirming network cable reseated, print queue cleared, confirmed by caller.</p>

---

## <p align="center">Reports and Dashboard</p>

### <p align="center">Reports</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1487414083081998387/image.png?ex=69c90dd0&is=69c7bc50&hm=4e1939ff6e033efe2423159c651b51a7edfe5d9cb643417d949918b46feac407&" alt="Reports" width="800"/>
</p>

<p align="center">Dashboard built covering L1 workload, open incidents, and incidents by category.</p>

### <p align="center">L1 Workload Config</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1487414223805091971/image.png?ex=69c90df1&is=69c7bc71&hm=7b720a014852c45bcd523b1776abef48c01b2b1dfeacb42c18dba4a64f6725cc&" alt="L1 workload config" width="800"/>
</p>

<p align="center">

  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1487424398804652063/image.png?ex=69c9176b&is=69c7c5eb&hm=21d3c77eff45a5d9e65ef5d0707932c7112a6853843189f381b716ca8be3664d&"  width="500"/>

</p>

<p align="center">Data Visualization widget configured to show open incidents assigned to IT Helpdesk L1.</p>

### <p align="center">Open Incidents Config</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1487414337093242950/image.png?ex=69c90e0c&is=69c7bc8c&hm=d006643d39401c6306005fb8da63c37ca74e3c816d09510ea4d983478d03adae&" alt="Open incidents config" width="800"/>
</p>

<p align="center">

  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1487424470481113138/image.png?ex=69c9177c&is=69c7c5fc&hm=1a3418093db0b8a012a93e5d3b28fcb549e403a4536f46a81f7a763369e7b76f&"  width="500"/>

</p>

<p align="center">Donut chart visualization showing open incidents grouped by priority.</p>

### <p align="center">Incidents by Category</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1487414427350470697/image.png?ex=69c90e22&is=69c7bca2&hm=2808f286875d3eca91a2ea52fdb2b503e58ea9e4ff823c2e11fc2202436a5666&" alt="Incidents by category" width="800"/>
</p>

<p align="center">

  <img src="https://cdn.discordapp.com/attachments/1483540272167129129/1487424529558016150/image.png?ex=69c9178a&is=69c7c60a&hm=13f604c0d6f6b029b0fc1a0bc5744ac658bb5319c29e833c1797c1a1e1aad35c&"  width="500"/>

</p>

<p align="center">Bar chart breakdown of incidents by category for the current month.</p>




---

