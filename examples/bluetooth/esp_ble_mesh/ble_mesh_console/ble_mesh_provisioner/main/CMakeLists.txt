set(srcs "ble_mesh_adapter.c"
        "transaction.c"
        "ble_mesh_cfg_srv_model.c"
        "ble_mesh_console_lib.c"
        "ble_mesh_console_main.c"
        "ble_mesh_console_system.c"
        "ble_mesh_reg_cfg_client_cmd.c"
        "ble_mesh_reg_gen_onoff_client_cmd.c"
        "ble_mesh_reg_test_perf_client_cmd.c"
        "ble_mesh_register_node_cmd.c"
        "ble_mesh_register_provisioner_cmd.c"
        "register_bluetooth.c")

idf_component_register(SRCS "${srcs}"
                    INCLUDE_DIRS  ".")
