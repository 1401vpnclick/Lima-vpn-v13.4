<?php
$pkgName = $_SERVER['HTTP_PKGNAME'];


if ($pkgName == "com.example.alertsmali")
{
    $json["title"] = "";
    $json["message"] = "برای ویرایش این برنامه زحمت زیادی کشیده شده است، لطفا در چنل ما عضو شوید.";
    $json["dismissable"] = false;
    $json["dismissTxt"] = "رد";
    $json["okTxt"] = "عضویت";
    $json["okUrl"] = "https://google.com";
    $json["status"] = "ok";
}else if ($pkgName == "com.example.newapp")
{
    $json["title"] = "";
    $json["message"] = "برای ویرایش این برنامه زحمت زیادی کشیده شده است، لطفا در چنل ما عضو شوید.";
    $json["dismissable"] = false;
    $json["dismissTxt"] = "رد";
    $json["okTxt"] = "عضویت";
    $json["okUrl"] = "https://google.com";
    $json["status"] = "ok";
}else
{
    $json["status"] = "nok";
}

die(json_encode($json));
?>
