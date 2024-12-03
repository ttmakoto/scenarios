# scenarios

notion link:
https://aged-domain-2e0.notion.site/Scenario-11eba509c1d38093982bd465899c4b52?pvs=4


source install/setup.bash

ros2 launch scenario_test_runner scenario_test_runner.launch.py   record:=false   scenario:='$(find-pkg-share scenario_test_runner)/scenario/sample.yaml'   sensor_model:=mibot_sensor_kit   vehicle_model:=mibot_vehicle        time_out:=500

