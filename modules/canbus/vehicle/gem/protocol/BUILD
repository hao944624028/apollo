load("//tools:cpplint.bzl", "cpplint")

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "canbus_gem_protocol",
    srcs = [
      "accel_cmd_67.cc",
      "accel_rpt_68.cc",
      "brake_cmd_6b.cc",
      "brake_motor_rpt_1_70.cc",
      "brake_motor_rpt_2_71.cc",
      "brake_motor_rpt_3_72.cc",
      "brake_rpt_6c.cc",
      "date_time_rpt_83.cc",
      "global_cmd_69.cc",
      "global_rpt_6a.cc",
      "headlight_cmd_76.cc",
      "headlight_rpt_77.cc",
      "horn_cmd_78.cc",
      "horn_rpt_79.cc",
      "lat_lon_heading_rpt_82.cc",
      "parking_brake_status_rpt_80.cc",
      "shift_cmd_65.cc",
      "shift_rpt_66.cc",
      "steering_cmd_6d.cc",
      "steering_motor_rpt_1_73.cc",
      "steering_motor_rpt_2_74.cc",
      "steering_motor_rpt_3_75.cc",
      "steering_rpt_1_6e.cc",
      "turn_cmd_63.cc",
      "turn_rpt_64.cc",
      "vehicle_speed_rpt_6f.cc",
      "wheel_speed_rpt_7a.cc",
      "wiper_cmd_90.cc",
      "wiper_rpt_91.cc",
      "yaw_rate_rpt_81.cc",

    ],
    hdrs = [
      "accel_cmd_67.h",
      "accel_rpt_68.h",
      "brake_cmd_6b.h",
      "brake_motor_rpt_1_70.h",
      "brake_motor_rpt_2_71.h",
      "brake_motor_rpt_3_72.h",
      "brake_rpt_6c.h",
      "date_time_rpt_83.h",
      "global_cmd_69.h",
      "global_rpt_6a.h",
      "headlight_cmd_76.h",
      "headlight_rpt_77.h",
      "horn_cmd_78.h",
      "horn_rpt_79.h",
      "lat_lon_heading_rpt_82.h",
      "parking_brake_status_rpt_80.h",
      "shift_cmd_65.h",
      "shift_rpt_66.h",
      "steering_cmd_6d.h",
      "steering_motor_rpt_1_73.h",
      "steering_motor_rpt_2_74.h",
      "steering_motor_rpt_3_75.h",
      "steering_rpt_1_6e.h",
      "turn_cmd_63.h",
      "turn_rpt_64.h",
      "vehicle_speed_rpt_6f.h",
      "wheel_speed_rpt_7a.h",
      "wiper_cmd_90.h",
      "wiper_rpt_91.h",
      "yaw_rate_rpt_81.h",
    ],
    deps = [
        "//modules/drivers/canbus/common:canbus_common",
        "//modules/canbus/proto:canbus_proto",
        "//modules/drivers/canbus/can_comm:message_manager_base",
    ],
)

cc_test(
    name = "accel_rpt_68_test",
    size = "small",
    srcs = [
        "accel_rpt_68_test.cc",
    ],
    deps = [
        "//modules/canbus/vehicle/gem/protocol:canbus_gem_protocol",
        "@gtest//:main",
    ],
)


cc_test(
    name = "brake_rpt_6c_test",
    size = "small",
    srcs = [
        "brake_rpt_6c_test.cc",
    ],
    deps = [
        "//modules/canbus/vehicle/gem/protocol:canbus_gem_protocol",
        "@gtest//:main",
    ],
)

cpplint()
