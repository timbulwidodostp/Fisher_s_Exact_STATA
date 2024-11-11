*------------------------------------Olah Data Semarang (timbulwidodostp)--------------------------------------*
*--------------------------------------------------WhatsApp : +6285227746673-----------------------------------*
*--------------------------------------------------IG : @olahdatasemarang_-------------------------------------*
*-----------------------------Fisher's Exact Test for Count Data Use tabulate With STATA 18--------------------*
*-------------------------Use (Open) File Input From Github Olah Data Semarang (timbulwidodostp)---------------*
import excel "https://raw.githubusercontent.com/timbulwidodostp/Fisher_s_Exact_STATA/main/Fisher_s_Exact_STATA/fisher.test.xlsx", sheet("Sheet1") firstrow clear
*----------------------------------------------Create Label Dependen-------------------------------------------*
label val Dependen Dependen
lab def Dependen 1 "Yes" 2"No"
*----------------------------------------------Create Label Independen-----------------------------------------*
label val Independen Independen
lab def Independen 1 "True" 2"False"
*------------------Estimation Fisher's Exact Test for Count Data Use tabulate With STATA 18--------------------*
tabulate Dependen Independen, exact
*-----------------------------Fisher's Exact Test for Count Data Use tabulate With STATA 18--------------------*
*------------------------------------Olah Data Semarang (timbulwidodostp)--------------------------------------*
*--------------------------------------------------WhatsApp : +6285227746673-----------------------------------*
*--------------------------------------------------IG : @olahdatasemarang_-------------------------------------*
*-----------------------------Fisher's Exact Test for Count Data Use tabulate With STATA 18--------------------*