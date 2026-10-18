# Anonymous Review Materials

Code, fixed inputs, saved outputs, and reproduction/verification scripts
for the diagnostic-stability experiments.

## Start here

1. Download `latest_joint_and_unit_materials.zip` and extract it.
2. Follow its README for the portable matched-acceptance unit-cost
   reproduction and the independent complete joint-evidence checker.
3. The other components contain their own READMEs, source and result manifests.

## Components

- [latest_joint_and_unit_materials.zip](latest_joint_and_unit_materials.zip): Latest joint-pattern results, unit-cost rules, and a portable matched-acceptance reproduction component.
- [public_cost_axes.zip](public_cost_axes.zip): Public cost-axis component: source, fixed inputs, and saved parameter-domain results.
- [unit_extension.zip](unit_extension.zip): Previously prepared unit-cost extension component.
- [saved_controls.zip](saved_controls.zip): Previously prepared controlled-experiment source and saved outputs.
- [saved_statistics.zip](saved_statistics.zip): Previously prepared saved statistics and aggregation material.

## Verification scope

The portable unit-cost component has been rerun after extraction into a
fresh location: all five references, 9,159 model/word inputs, and 59,634
restoration comparisons agreed with the frozen results. The joint-evidence
checker independently verified all 18,318 endpoint families and 59,634
comparisons. Execution instructions and receipts are included in the
latest component.

The cost-axis component includes its full-run entry point and saved
certificates. Its fresh relocated prepare/pilot run passed; the previously
recorded full run also passed. Component READMEs distinguish runnable
entry points, source requiring configuration, and frozen outputs.

## Sources and licenses

Third-party implementations and data retain their original sources and
license information inside the component archives. Consult those records
before reuse or redistribution. This release contains no manuscript,
author list, email correspondence, or local-machine paths.
