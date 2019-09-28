<?php

  // Get cURL resource
  $curl = curl_init();

  // Set some options
  curl_setopt_array($curl, array(
    CURLOPT_URL => 'https://htmlpdfapi.com/examples/simple.html'
  ));

  // Send the request & save response to $resp
  $resp = curl_exec($curl);

  // Output results
  echo $resp;

  // Close request to clear up some resources
  curl_close($curl);
