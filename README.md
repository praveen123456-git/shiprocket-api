# shiprocket-api
Shiprocket Api for codeigniter

Usage ::
load this library in controllers

$this->load->library('shiprocket');

Example ::

$post['pickup_postcode'] = 560072;

$post['cod'] = 0;

$shipState = $this->shiprocket->serviceability($post);

