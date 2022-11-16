 $baglan = curl_init();
    curl_setopt($baglan, CURLOPT_URL, "https://www.sahibinden.com/");
    curl_setopt($baglan, CURLOPT_RETURNTRANSFER, true);
    curl_setopt($baglan, CURLOPT_FOLLOWLOCATION, TRUE);
    curl_setopt($baglan, CURLOPT_SSL_VERIFYPEER, false);
    curl_setopt($baglan, CURLOPT_USERAGENT, "Mozilla/5.0 (platform; rv:geckoversion) Gecko/geckotrail Firefox/firefoxversion");
    curl_setopt($baglan, CURLOPT_REFERER, "https://www.google.com/");
    $sonuc = curl_exec($baglan);
    curl_close($baglan);
