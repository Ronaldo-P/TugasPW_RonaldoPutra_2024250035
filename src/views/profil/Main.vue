<template>
    <div>
        <layout-main>
            <div class="d-flex justify-content-between flex-wrap flex-md-nowrap align-items-center pt-3 pb-2 mb-3 border-bottom">
                <h1 class="h2">Profil</h1>
            </div>
                        
            
            <hr>
            <div class="row">
                
                <div class="col">
                <h5><u>Biodata</u></h5>
                <li>Lahir di Palembang, 2 Juli 2002</li>
                <li>Anak ke-3 dari 4 bersaudara</li>
                <li>Tinggal di Jl. Slamet Riady No 255</li>
                <li>Beragama Buddha</li>
                <li>Jenis Kelamin Laki-laki</li>
                <li>Merupakan Mahasiswa MDP</li>
                <li>Bekerja di Kedai B217an</li>
                </div>

                <div class="col">
                    <h5><u>Pendidikan</u></h5>
                    <li>SD SUMSEL JAYA</li>
                    <li>SMP METHODIST 2</li>
                    <li>SMK METHODIST 2</li>
                    <li>UNIVERSITAS MDP</li>
                </div>

            </div>
            
        </layout-main>
    </div>
</template>

<script>
import LayoutMain from "@/views/LayoutMain"
export default {
    components: {
        LayoutMain
    }
}
</script>