# Blair legacy Venus backend

Stock fogos/rhodep VIDEO.VE.6.0 firmware uses the legacy HFI packet format (SYS_INIT=0x00010001), not the newer compound HFI packets used by driver/vidc (INIT=0x01000001). Select this backend only for CONFIG_ARCH_BLAIR and retain the msm_video module name.

Source reference: PocoF3Development/android_vendor_qcom_opensource_video-driver-5.15, commit 73e287e3cbb7e041615f30296263ab5da15c9cd2, legacy Qualcomm driver with DMA-heap/interconnect adaptations. The donor is archived and does not claim production validation. Blair integration must be reviewed and tested independently. Qualcomm/Google/Motorola licenses remain in source files.
