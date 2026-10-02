# abroad
Hab dich lieb!
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unsere Fotos</title>
    <style>
        body {
            margin: 0;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: #f5f5f5;
        }
        img {
            max-width: 95vw;
            max-height: 95vh;
            object-fit: contain;
        }
    </style>
</head>
<body>

    <img id="foto" alt="Foto">

    <script>
        // Wartet, bis das HTML vollständig geladen ist
        document.addEventListener("DOMContentLoaded", () => {
            const fotos = [
                "1odAWoW_KdbkKQ_bUxIbqjIj_Lcbh13A4", "1wRPdptqnyFVvwPxbHRqKlJL76TYhyr9y", 
                "1cGKYFiloS8Pb2eT1-TEt0ULVB3cnAcau", "1HdX8QufkkeP04CVJCevm2Xd7WFv15yrl", 
                "147A6kT1UOBOlrC5Cc3piqgL414cmp5Rl", "1QW1E1FmmG09zYwfFb74c-fGgN9BHbpSC", 
                "1zrWBqRvApuAVRgPnrnQVevt2PYpbVDXu", "1HGpuG8mvggugDQl2YlokJxxMTPuGdCtX", 
                "1_-bbXEct9gir76FAkzTFbl3XlDy-EXrw", "1YfeTiwCWdA7hK8sMYRgcL8Ik06MuW4jy", 
                "1PvwGTFqZiEAEFMBXt5p6St168ZMh34VG", "1SQS5vq98AwDU_FE2O9pH0VD9zpCJ1I4f", 
                "1nwW8pLnxD22qysYYDDBBjL-xqEk3bgL4", "1QGpEQQsS6iODdlIq4d02fWaKaejeK05i", 
                "1eFlVUTc-bm5MPllDzcveSobW7NPUKjBI", "1z1_HQa_w_Hr2IPjqHe-EF485P6bnZpas", 
                "13S2x8Yf86yq1t0vg_Fc_jTroKL68dyQ6", "17YZGcEHSVNlt_YwvKlsSdwQCDVND81dr", 
                "1wlxNZ4Ykg88SLT-L9f22G-OxvVFH3GXY", "14KSLZd1TixPilcIJgDeKGXvhZ79wRhA7", 
                "1DrdxsN3xWdeDzHMG6pq8R9z9_Uu_1u2e", "1UxV4n-fGhIbTQZo4rDAE0NaZiV_4RUue", 
                "1burVfUt1HrdbP8PB_63XJ-Fo6BLuR7As", "1XeBTBtXWEm27tbCSDjvvDzkgdzv7UQMR", 
                "1cslbT_RcwSpo0HRytH_nJsbXK5RKxkty", "1Bl8wXrZEMzFvoIi_u5RaHMbAZFVTYmFT", 
                "1OKRfk53SW7Vk8UDWNjhzCosGEHXgIDtB", "1z6uO1spe-gpe6cNBopCjaen92Dyv6soO", 
                "1ULrxCxfmboV1ha5c67eRRCa1dBWl2MEE", "1G3LBeBYwkoG1ag5sINj7joTmq6uG_OLr", 
                "1zrMndDjtDMv_kQFx2C_sHOsRX9v7PFq5", "17AM_-A00cjdOrrW2pz-uiZTp_x-6L12w", 
                "1nJFVXQ6xdWmCkGHNe6AROjhkpFq4qpyi", "17fd9v9a48O9iNlmN60-IBoWLeDlXRinD", 
                "1_9QEXXNvzinodWLmb9-ZRXIbsUQkK8H1", "1wQfwjI3RUWdKbFD50pLPgDRwbB6O39iR", 
                "1f2JejFwOnfBXPkjavpXICln5Mj8Vle6h", "1E_YCwJrsvU5qM5WfuB-T87sUXl4LIQfE", 
                "1mIxDGQoyOMDl8kFSBdWJWLuPiOux_2iF"
            ];
            
            const zufall = Math.floor(Math.random() * fotos.length);
            document.getElementById("foto").src = "https://drive.google.com/thumbnail?id=" + fotos[zufall] + "&sz=w2000";
        });
    </script>
</body>
</html>
