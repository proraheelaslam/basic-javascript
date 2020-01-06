public function getTimeDifferenceByTimeSlot($startTime,$endTime,$timeSlot = 30,$timeGap = 5){

    $arrayOftime = [];
    $start_time  = strtotime($startTime);
    $end_time    = strtotime($endTime);
    if($end_time < $start_time){
        $added_date = date('Y-m-d H:i:s', strtotime('+1 day', $end_time));
        $end_time = strtotime($added_date);
    }

    $addMins  =  $timeSlot * 60;
    $timeGap  =  $timeGap * 60;



    while ($start_time <= $end_time)
    {
        $first_time = date("h:i a", $start_time);

        $arrayOftime[] = $first_time;
        $start_time += $addMins;
        $start_time += $timeGap;
    }


    return $arrayOftime;
}
