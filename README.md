# laravel9-google-maps

**Cara menghubungkan google maps ke laravel-9 tanpa package

masukkan script ini ke dalam views yang ingin ditampilkan google maps (cek bagian folder views)

<script type="text/javascript">
        function initMap() {
        // modified this lat and lng according to your place
          const myLatLng = { lat: -8.0739198, lng: 112.6063613 };
          const map = new google.maps.Map(document.getElementById("map"), {
            zoom: 5,
            center: myLatLng,
          });
  
          new google.maps.Marker({
            position: myLatLng,
            map,
            title: "test satu",
          });
        }
  
        window.initMap = initMap;
    </script>
