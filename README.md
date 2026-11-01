# Automation Dashboard

Usage statistics and ROI reporting for Red Hat Ansible Automation Platform.

## Contents

| File | Description |
|---|---|
| `roi_demo.yml` | Simulated maintenance task. Produces realistic job runtimes so Automation Analytics has data to report on. |

`roi_demo.yml` is a data generator, not real work: it timestamps, sleeps, and
timestamps again. Several job templates run it under different names so the
analytics view shows a spread of automation activity.

Job templates are tagged for grouping in Automation Analytics — see
`utils/tag_jts.yml` in the `aap_autodeploy_configascode` repository.

TODO: automate all the Dashboard Setup in AAP
