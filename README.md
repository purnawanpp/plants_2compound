# Simulasi penambatan 2 senyawa menggunakan PLANTS di google colab 

### Preparation and Molecular Docking
1. Download amfoterisin B dan Beta Cyclodextrin di pubchem
2. ubah nama filenya, senyawa  amfoterisin B menjad **lig.sdf** dan beta cyclodextrin menjadi **rec.sdf**
3. Buka file lig.sdf dan rec.sdf tadi di avogadro dan lakukan optimasi geometri pilih extension > Molecular Mechanics > Setup force field > Pilih UFF lalu ok > extension  > optimize geometry simpan masing-masing lig.sdf menjadi lig.pdb dan rec.sdf menjadi rec.pdb
4. Open file rec.pdb in the chimera, Tools > Structure Editing > Dock Prep > Ok > Ok > On Assign Charges for dock prep click Gasteiger and standard residues > File > Save PDB > save file namely rec.mol2 file
5. Open lig.pdb in chimera, Tools > Structure Editing > Dock Prep > Ok > Ok > On Assign Charges for dock prep click Gasteiger and nonstandard residues > File > Save PDB > save file namely lig.mol2
6. Jalankan google colab berikut ini: https://github.com/purnawanpp/plants_2compound/blob/main/plants.ipynb
7. Upload file rec.mol2 dan lig.mol2 di google colab
8. Eksekusi semua perintah google colab satu persatu

### Reference:
1. https://github.com/purnawanpp/plants/blob/main/plants_manual1.2.pdf
2. https://github.com/purnawanpp/plants/blob/main/spores_manual.pdf
3. https://github.com/purnawanpp/plants/blob/main/plants_article.pdf
4. https://github.com/purnawanpp/plants/blob/main/spores_article.pdf
