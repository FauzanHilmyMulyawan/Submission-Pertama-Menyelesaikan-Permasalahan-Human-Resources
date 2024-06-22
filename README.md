# Submission-Pertama-Menyelesaikan-Permasalahan-Human-Resources

## Latar Belakang

Jaya Jaya Maju adalah perusahaan multinasional yang telah beroperasi sejak tahun 2000, dengan lebih dari 1000 karyawan tersebar di seluruh negeri. Meskipun telah berkembang menjadi entitas yang cukup besar, perusahaan ini masih menghadapi tantangan dalam mengelola karyawan, yang tercermin dari tingginya rasio attrition yang mencapai lebih dari 10%. Untuk mengatasi masalah ini, manajer departemen HR memerlukan bantuan dalam mengidentifikasi faktor-faktor yang berkontribusi terhadap tingginya tingkat keluar-masuk karyawan, serta dalam membuat dashboard bisnis yang dapat memonitor berbagai faktor tersebut secara efektif.

## Permasalahan Bisnis

Jaya Jaya Maju menghadapi tingkat attrition yang tinggi, melebihi 10%, yang dapat mengganggu stabilitas operasional dan meningkatkan biaya rekrutmen serta pelatihan. Untuk mengatasi masalah ini, manajer HR memerlukan bantuan untuk mengidentifikasi berbagai faktor yang berkontribusi terhadap tingginya tingkat attrition, seperti keseimbangan kerja-hidup, kepuasan kerja, peluang karir, kompensasi, dan lingkungan kerja. Selain itu, diperlukan juga alat atau dashboard bisnis yang dapat membantu memonitor secara real-time faktor-faktor tersebut, memungkinkan manajer HR untuk mengambil tindakan preventif dan korektif yang tepat waktu.

## Cakupan Proyek
### Tujuan Proyek
Mengidentifikasi Faktor Penyebab Tinggi Tingkat Attrisi
Mengembangkan Dashboard Bisnis untuk Pemantauan Real-Time

### Langkah-Langkah Proyek
Download Data
Eksplorasi dan Pembersihan Data
Analisis Data
Pengembangan Dashboard Bisnis

## Persiapan
Sumber data: https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee

Setup Environment - Anaconda:
<div style="border: 1px solid black; padding: 10px;">
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt
</div>


Setup Environment - Shell/Terminal:
<div style="border: 1px solid black; padding: 10px;">
mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt
</div>


## Business Dashboard

Dashboard : https://public.tableau.com/views/Dashboard_17183339366460/Dashboard1?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link

Dari overtime (lembur), pegawai yang sering lembur, akan cenderung melakukan atrisi

Dari bidang pendidikan, pegawai yang berasal dari ilmu biologi cenderung melakukan atrisi

Dari gender, pegawai pria cenderung melakukan atrisi

Dari posisi, teknisi labnoratorium cenderung melakukan atrisi

Dari perjalanan bisnis, pegawai yang jarang melakukan perjalanan bisnis cenderung melakukan atrisi

## Conclusion

Jaya Jaya Maju, sebuah perusahaan multinasional dengan lebih dari 1000 pegawai, menghadapi tantangan signifikan dalam mengelola tingkat attrisi yang tinggi, melebihi 10%. Tingginya tingkat keluar-masuk pegawai ini tidak hanya mengganggu stabilitas operasional tetapi juga meningkatkan biaya rekrutmen dan pelatihan. Berdasarkan analisis data yang dilakukan, beberapa faktor kunci yang berkontribusi terhadap tingginya tingkat attrisi telah diidentifikasi:

Overtime (Lembur): Pegawai yang sering melakukan lembur menunjukkan kecenderungan yang lebih tinggi untuk melakukan attrisi. Ini menunjukkan bahwa beban kerja yang berlebihan dan ketidakseimbangan antara kehidupan kerja dan pribadi dapat menjadi faktor signifikan dalam keputusan pegawai untuk meninggalkan perusahaan.

Bidang Pendidikan: Pegawai yang memiliki latar belakang pendidikan di bidang ilmu biologi cenderung lebih tinggi tingkat attrisinya dibandingkan dengan pegawai dari bidang pendidikan lainnya. Hal ini dapat menunjukkan ketidakcocokan antara kualifikasi pendidikan dan ekspektasi pekerjaan atau kurangnya peluang pengembangan karir yang sesuai dengan latar belakang pendidikan tersebut.

Gender: Analisis juga menunjukkan bahwa pegawai pria cenderung lebih tinggi tingkat attrisinya dibandingkan dengan pegawai wanita. Faktor ini mungkin terkait dengan berbagai alasan, termasuk perbedaan dalam persepsi tentang peluang karir, keseimbangan kerja-hidup, atau budaya kerja yang ada di perusahaan.

## Rekomendasi

Untuk mengatasi masalah ini, manajer HR memerlukan dashboard bisnis yang efektif yang dapat memonitor secara real-time berbagai faktor yang berkontribusi terhadap attrisi. Dengan alat ini, manajer dapat mengidentifikasi masalah lebih awal dan mengambil tindakan preventif dan korektif yang tepat waktu. Beberapa langkah yang bisa diambil meliputi:

Mengurangi beban kerja dan mengatur kebijakan lembur yang lebih seimbang.
Menyediakan peluang pengembangan karir yang lebih sesuai dengan latar belakang pendidikan pegawai.
Meningkatkan program retensi pegawai yang lebih inklusif dan mendukung keseimbangan kerja-hidup yang lebih baik.
Dengan demikian, perusahaan dapat mengurangi tingkat attrisi, meningkatkan kepuasan dan retensi pegawai, serta mengurangi biaya yang terkait dengan pergantian pegawai
