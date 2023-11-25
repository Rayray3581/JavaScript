# JavaScript
return mixed  */  public function getStatusInfo(  $info = null,  $force_read = false,  $disable_error = false  ) {  $db = $this->_db_name;  $table = $this->_name;  if (!empty($_SESSION['is_mult $disable_error = true; }  // sometimes there is only one
