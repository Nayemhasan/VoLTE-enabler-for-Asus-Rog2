# VoLTE-enabler-for-Asus-Rog2🍉
This module Enables the VoLTE &amp; VoWiFi options for Asus Rog Phone 2 by editing build.prop.

## What does this module change?
    # persist
    persist.data.iwlan=1
    persist.data.iwlan.enable=true
    persist.data.iwlan.ipsec.ap=1
    # debug
    persist.dbg.ims_volte_enable=1
    persist.dbg.volte_avail_ovr=1
    persist.dbg.vt_avail_ovr=1
    persist.dbg.allow_ims_off=1
    persist.dbg.wfc_avail_ovr=1
    # radio
    persist.radio.calls.on.ims=1
    persist.radio.data_con_rprt=1
    persist.radio.data_ltd_sys_ind=1
    persist.radio.dynamic_sar=false
    persist.radio.force_on_dc=true
    persist.radio.NO_STAPA=1
    persist.radio.rat_on=combine
    persist.radio.VT_ENABLE=1
    persist.radio.VT_HYBRID_ENABLE=1
    persist.radio.volte.dan_support=true
    # vendor
    persist.vendor.dpm.feature=1
    persist.vendor.radio.calls.on.ims=1
    persist.vendor.radio.data_con_rprt=1
    persist.vendor.radio.data_ltd_sys_ind=1
    persist.vendor.radio.enable_temp_dds=true
    persist.vendor.radio.force_ltd_sys_ind=1
    persist.vendor.radio.force_on_dc=true
    persist.vendor.radio.manual_nw_rej_ct=1
    persist.vendor.radio.mbn_load_flag=3
    persist.vendor.radio.mbn_wait_s=60
    persist.vendor.radio.redir_party_num=1
    # extras
    persist.sys.cust.lte_config=true
    persist.sys.strictmode.disable=true
    persist.rcs.supported=1
    
<table>
  <tr>
    <td>Before</td>
    <td>After</td>
   </tr> 
   <tr>
      <td><img src="https://github.com/Nayemhasan/VoLTE-enabler-for-Asus-Rog2/blob/main/pics/before.jpg"></td>
      <td><img src="https://github.com/Nayemhasan/VoLTE-enabler-for-Asus-Rog2/blob/main/pics/after.jpg"></td>
  </tr>
</table>   
 
## Dependencies
Use the latest [Magisk](https://magiskmanager.com/) manager

## How to use?
 - flash the latest released .zip with magisk
 - reboot and profit*
 
## Bonus
Now you can use 4G Dual* Sim mode too😉

## Thank You🍉

