# int-pilih-0-pilih-cbxSekolah.getSelectedIndex-cbxJurusan.removeAllItems-
int pilih = 0;        pilih = cbxSekolah.getSelectedIndex();        cbxJurusan.removeAllItems();        cbxJurusan.addItem("==PILIH JURUSAN==");        switch(pilih){            case 1:  //SMKN 1 MALANG                cbxJurusan.addItem("PERHOTELAN");                cbxJurusan.addItem("TATA BOGA");                cbxJurusan.addItem("AKUTANSI");                cbxJurusan.addItem("AGRIBISNIS");                cbxJurusan.addItem("TKJ");                break;            case 2:  //SMKN 2 MALANG                cbxJurusan.addItem("PERHOTELAN");                cbxJurusan.addItem("TATA BOGA");                cbxJurusan.addItem("TKJ");                break;            case 3:  //SMKN 3 MALANG                cbxJurusan.addItem("PERHOTELAN");                cbxJurusan.addItem("TATA BOGA");                cbxJurusan.addItem("AKUTANSI");                cbxJurusan.addItem("TATA BUSANA");                cbxJurusan.addItem("TKJ");                break;            case 4:  //SMKN 4 MALANG                cbxJurusan.addItem("PERHOTELAN");                cbxJurusan.addItem("RPL");                cbxJurusan.addItem("DKV");                cbxJurusan.addItem("ANM");                cbxJurusan.addItem("TKJ");                break;        }     }
