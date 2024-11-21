Latest Logs From Latest Build
==============================

Generated On: 2024-11-21 17:32:38 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/Rroberts12Seneca/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-21_17:24:56] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-21_17:24:59] STEP 2: Create topics started

  [INFO 2024-11-21_17:25:12] STEP 2: Completed

  [INFO 2024-11-21_17:25:18] STEP 3: producing data started

  [INFO 2024-11-21_17:25:21] MQTT connection established...

  [INFO 2024-11-21_17:25:21] STEP 4: Preprocessing started

  [INFO 2024-11-21_17:25:23] STEP 4: Preprocessing started

  [INFO 2024-11-21_17:25:25] STEP 7: Visualization started

  [INFO 2024-11-21_17:25:31] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-11-21_17:25:36] STEP 9: Starting privateGPT

  [INFO 2024-11-21_17:25:44] STEP 8: Starting docker push for: rroberts87/cyt160cybersecurityprojectgr2-4651-amd64

  [INFO 2024-11-21_17:26:02] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-11-21_17:26:12] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 42a0052a9b46 rroberts87/cyt160cybersecurityprojectgr2-4651-amd64 - message=0

  [INFO 2024-11-21_17:32:01] STEP 8: Successfully ran Docker push: docker push rroberts87/cyt160cybersecurityprojectgr2-4651-amd64 - message=0

  [INFO 2024-11-21_17:32:37] STEP 10: Started to build the documentation

  [INFO 2024-11-21_17:32:39] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


