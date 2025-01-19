<template>
  <div>
    <h1>Random Fake Emails List</h1>

    <!-- Table with CSV data -->
    <table border="1" cellpadding="5" cellspacing="0">
      <thead>
        <tr>
          <th>Email</th>
          <th>First Name</th>
          <th>Last Name</th>
          <th>Gender</th>
          <th>Address</th>
          <th>City</th>
          <th>Institute</th>
          <th>Batch</th>
          <th>Phone Number</th>
          <th>isEnrolled</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>azzn.naveed@gmail.com</td>
          <td>Azlan</td>
          <td>Naveed</td>
          <td>Male</td>
          <td>Village Yugo, Tehsil Khaplu, District Ghanche, Gilgit Baltistan</td>
          <td>Gilgit</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0343-5982892</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>samrahriaz1998@gmail.com</td>
          <td>Samrah</td>
          <td>Riaz</td>
          <td>Female</td>
          <td>House No.ZB-6683, Street No.26/A, Bangash Colony, Pirwadhai, Rawalpindi</td>
          <td>Rawalpindi</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0347-1951771</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>shanzayazeem10@gmail.com</td>
          <td>Shanzay</td>
          <td>Azeem</td>
          <td>Female</td>
          <td>House No.579, Block No.F, Satellite Town, Rawalpindi</td>
          <td>Rawalpindi</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0304-4556236</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>bobthebutiful@gmail.com</td>
          <td>Muhammad</td>
          <td>Talha</td>
          <td>Male</td>
          <td>House No.SD -189, Lane No.2, Askari Colony No.2, Multan Cantt</td>
          <td>Multan</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0311-4701572</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>navazish85@gmail.com</td>
          <td>Navazish</td>
          <td>Jahan</td>
          <td>Male</td>
          <td>Village Jandrote,P.O Gupis,Tehsil & District Ghizer, Gilgit Baltistan</td>
          <td>Gilgit</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0315-1014290</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>nimraomer19@gmail.com</td>
          <td>Nimra</td>
          <td>Noor</td>
          <td>Female</td>
          <td>House No.B-II-29-S-4, Machine Mohallah No.3, Galli Doctoran, Jehlum</td>
          <td>Jehlum</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0342-5315809</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>alexbasit32@gmail.com</td>
          <td>Abdul</td>
          <td>Khan</td>
          <td>Male</td>
          <td>House No.11, Azizabad Colony, Vehari Road, Tehsil Hasil Pur, District Bahawalpur</td>
          <td>Bahawalpur</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0300-0032320</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>hhamzaarshad427@gmail.com</td>
          <td>Muhammad</td>
          <td>Arshad</td>
          <td>Male</td>
          <td>House No.C.B 1598, Street No.51, Allama Iqbal Colony, Rawalpindi</td>
          <td>Rawalpindi</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0345-5358021</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>asadali51051@gmail.com</td>
          <td>Asad</td>
          <td>Ali</td>
          <td>Male</td>
          <td>House No.42, Street No.21, Nayyar Colony, Chaklala Scheme III, Rawalpindi</td>
          <td>Rawalpindi</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0306-0122333</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>hamxa1056@gmail.com</td>
          <td>Hamza</td>
          <td>Ali</td>
          <td>Male</td>
          <td>Village Mohra Dakhali Kalanwan, P.O Sarai Saleh, Tehsil & District Haripur</td>
          <td>Haripur</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0310-5273742</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>hurairaidrees@gmail.com</td>
          <td>Muhammad</td>
          <td>Huraira</td>
          <td>Male</td>
          <td>House No.CB-3983/5, Street No.54/2, Allama Iqbal Colony, Rawalpindi</td>
          <td>Rawalpindi</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0348-0522988</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>muhammadsamiuddrafay@gmail.com</td>
          <td>Muhammad</td>
          <td>Sami Ud Din</td>
          <td>Male</td>
          <td>House No.8, Block No.50, Sodiwal Colony, Lahore</td>
          <td>Lahore</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0336-4338484</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>samia.bukhari9@gmail.com</td>
          <td>Syeda</td>
          <td>Samia</td>
          <td>Female</td>
          <td>House No.491, Street No.65, Pakistan Town Phase I, Rawalpindi</td>
          <td>Rawalpindi</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0336-5985234</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>ali.sandhu4477@gmail.com</td>
          <td>Ali</td>
          <td>Hamza</td>
          <td>Male</td>
          <td>Flat No.J2/3, Army Flats, Chungi No.22, Rawalpindi Cantt</td>
          <td>Rawalpindi</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0315-1504010</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>na131202@gmail.com</td>
          <td>Nabeel</td>
          <td>Ali</td>
          <td>Male</td>
          <td>House No.CB-290, Mohallah Tench Bhatta Abadi No.2, Rawalpindi</td>
          <td>Rawalpindi</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0336-8866202</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>afaqayub63@gmail.com</td>
          <td>Muhammad</td>
          <td>Afaq</td>
          <td>Male</td>
          <td>House No.BV-183, Nishtar Street, Muslim Town, Sadiqabad, Rawalpindi</td>
          <td>Rawalpindi</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>-</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>relaxineint@gmail.com</td>
          <td>Muhammad</td>
          <td>Umer</td>
          <td>Male</td>
          <td>House No.62, Islam Nagar Road, Pacca Ghara, Sialkot</td>
          <td>Sialkot</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0331-6134006</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>faharullah@gmail.com</td>
          <td>Muhammad</td>
          <td>Fahar Ullah</td>
          <td>Male</td>
          <td>House No.217, Street No.2, Model Town Humak, Islamabad</td>
          <td>Islamabad</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0331-9945868</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>nawazkhattak391@gmailc.om</td>
          <td>Yasir</td>
          <td>Nawaz</td>
          <td>Male</td>
          <td>P.O Kahi Nizampur, Tehsil & District Nowshera, KPK</td>
          <td>Nowshera</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>-</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>fahadtariq1999@gmail.com</td>
          <td>Fahad</td>
          <td>Tariq</td>
          <td>Male</td>
          <td>House No.Z-557/3, Mohallah Babu Lal Hussain Road, Nai Abadi, Miladnagar, Rawalpindi</td>
          <td>Rawalpindi</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0312-5688323</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>waqasibnesalman@gmail.com</td>
          <td>Muhammad</td>
          <td>Waqas</td>
          <td>Male</td>
          <td>House No.A-91, Rafah-e-Aam Society, Malir Halt, Karachi</td>
          <td>Karachi</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0331-2227359</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>etee127@gmail.com</td>
          <td>Maham</td>
          <td>Tahir</td>
          <td>Female</td>
          <td>House No.718, Street No.3, Sector I-10/2, Islamabad</td>
          <td>Islamabad</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0330-5490971</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>ibtisam.tanveer22@gmail.com</td>
          <td>Muhammad</td>
          <td>Tanveer</td>
          <td>Male</td>
          <td>House No.107, Waheed Brothers Colony, Ferozpur Road, Lahore</td>
          <td>Lahore</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0324-4302129</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>chahsanshabbir5@gmail.com</td>
          <td>Ahsan</td>
          <td>Shabbir</td>
          <td>Male</td>
          <td>Street No.5, Lane No.6, Pir Mehr Ali Shah Town, Chakri Road, Rawalpindi</td>
          <td>Rawalpindi</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0316-5068634</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>syedaizazshahkazmi@gmail.com</td>
          <td>Syed</td>
          <td>Aizaz Hussain</td>
          <td>Male</td>
          <td>Village & P.O Kot Fateh Khan, Tehsil Fateh Jang, District Attock</td>
          <td>Fateh Jang</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0343-5004032</td>
          <td>FALSE</td>
        </tr>
        <tr>
          <td>ansariqbalpk786@gmail.com</td>
          <td>Ansar</td>
          <td>Iqbal</td>
          <td>Male</td>
          <td>House No.376, Street No.3, Model Town Humak, Islamabad</td>
          <td>Islamabad</td>
          <td>NuTech University</td>
          <td>2018</td>
          <td>0304-5237065</td>
          <td>FALSE</td>
        </tr>
      </tbody>
    </table>

    <hr />

    <!-- Extra random emails scattered for testing -->
    <div>
      <p>Here are some random emails:
        <b>demo@example.com</b>,
        <i>test123@fakemail.org</i>,
        <span>contact@something.co</span>
      </p>
      <p>
        Another set:
        <u>user.name+alias@mydomain.com</u>,
        <strong>someone_else@domain.net</strong>
      </p>
    </div>
  </div>
</template>

<script setup>
  /*
    This is just a demo page, no special logic here.
    Your script that collects emails can run on this page
    to pick them out of the DOM.
  */
</script>

<style scoped>

  /* Just some quick styling for clarity */
  table {
    width: 100%;
    margin-bottom: 20px;
  }

  th {
    background-color: #eee;
  }
</style>
