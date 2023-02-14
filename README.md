# ONEPLUS SM8450 Opensource kernel build
### Based on 
 + [oneplus  opensource kernel for sm8450](https://github.com/OnePlusOSS/android_kernel_msm-5.10_oneplus_sm8450) -b oneplus/sm8450_t_13.0_10pro
 + [kernel modules](https://github.com/OnePlusOSS/android_kernel_modules_and_devicetree_oneplus_sm8450) -b oneplus/sm8450_t_13.0_10pro
 + [gck common-android12-5.10](https://source.android.com/docs/setup/build/building-kernels)

### How to build
> * cd kernel_platform
> * SKIP_MRPROPER=1 AGING_DEBUG_MASK=2 LTO=full BUILD_CONFIG=common/build.config.msm.waipio VARIANT=gki ./build/build.sh
