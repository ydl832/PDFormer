# PDFormer
The code for "PDFormer: A Multimodal Transformer for Quantifying Motor Symptom Severity in Parkinson’s Disease" is coming.
<table>
  Examples of finger-tapping sequences from the PDMotorDB dataset. The labeled scores are taken directly from the original records in the dataset.
  <tr>
    <td align="center">
      <img src="demos/0_raw.gif" width="260"/><br/>
      <b>Finger Tapping (Score 0)</b>
    </td>
    <td align="center">
      <img src="demos/1_raw.gif" width="260"/><br/>
      <b>Finger Tapping (Score 1)</b>
    </td>
    <td align="center">
      <img src="demos/2_raw.gif" width="260"/><br/>
      <b>Finger Tapping (Score 2)</b>
    </td>
    <td align="center">
      <img src="demos/3_raw.gif" width="260"/><br/>
      <b>Finger Tapping (Score 3)</b>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="demos/1_3d.gif" width="260"/><br/>
      <b>3D skeleton motion (Score 0)</b>
    </td>
    <td align="center">
      <img src="demos/0_3d.gif" width="260"/><br/>
      <b>3D skeleton motion (Score 1)</b>
    </td>
      <td align="center">
      <img src="demos/2_3d.gif" width="260"/><br/>
      <b>3D skeleton motion (Score 2)</b>
    </td>
    </td>
      <td align="center">
      <img src="demos/3_3d.gif" width="260"/><br/>
      <b>3D skeleton motion (Score 3)</b>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="demos/0_motion.gif" width="260"/><br/>
      <b>Dinov2 motion (Score 0)</b>
    </td>
    <td align="center">
      <img src="demos/1_motion.gif" width="260"/><br/>
      <b>Dinov2 motion (Score 1)</b>
    </td>
      <td align="center">
      <img src="demos/2_motion.gif" width="260"/><br/>
      <b>Dinov2 motion (Score 2)</b>
    </td>
    </td>
      <td align="center">
      <img src="demos/3_motion.gif" width="260"/><br/>
      <b>Dinov2 motion (Score 3)</b>
    </td>
  </tr>
</table>
<table>
  Examples of 3D hand pose estimations for detecting motor symptoms in the hands.
  <tr>
    <td align="center">
      <img src="demos/finger_tapping.gif" width="260"/><br/>
      <b>Finger Tapping</b>
    </td>
    <td align="center">
      <img src="demos/hand_movements.gif" width="260"/><br/>
      <b>Hand Movements</b>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="demos/Pronation-supination.gif" width="260"/><br/>
      <b>Pronation-Supination</b>
    </td>
    <td align="center">
      <img src="demos/postural_tremor.gif" width="260"/><br/>
      <b>Postural Tremor</b>
    </td>
      <td align="center">
      <img src="demos/rest_tremor_hand.gif" width="260"/><br/>
      <b>Rest Tremor (hand)</b>
    </td>
  </tr>
</table>
<table>
  Examples of 3D whole-body pose estimations for detecting motor symptoms.
  <tr>
    <td align="center">
      <img src="demos/gait_03_3d.gif" width="260"/><br/>
      <b>Gait</b>
    </td>
    <td align="center">
      <img src="demos/gait_04_3d.gif" width="260"/><br/>
      <b>Gait</b>
    </td>
    <td align="center">
      <img src="demos/freezing.gif" width="260"/><br/>
      <b>Freezing of Gait</b>
    </td>
  </tr>
</table>
<table>
  Examples of 2D pose estimation for half-body and multi-person motor symptom assessment, such as Leg agility or Postural Stability.
  <tr>
    <td align="center">
      <img src="demos/Leg_agility.gif" width="260"/><br/>
      <b>Leg agility</b>
    <td align="center">
      <img src="demos/arising_from_chair.gif" width="260"/><br/>
      <b>Arising from Chair</b>
    <td align="center">
      <img src="demos/pose_stability.gif" width="260"/><br/>
      <b>Postural Stability</b>
    </td>
  </tr>
</table>
<table>
  Examples of DinoV2 motion features for other motor symptoms.
  <tr>
    <td align="center">
      <img src="demos/yande_leg_motion.gif" width="260"/><br/>
      <b>Leg agility</b>
    <td align="center">
      <img src="demos/yande_arising_motion.gif" width="260"/><br/>
      <b>Arising from Chair</b>
    <td align="center">
      <img src="demos/yande_rest_motion.gif" width="260"/><br/>
      <b>Rest tremor</b>
    </td>
    <td align="center">
      <img src="demos/yande_3_motion.gif" width="260"/><br/>
      <b>Postural tremor</b>
    </td>
    <td align="center">
      <img src="demos/yande_pos_tre_motion.gif" width="260"/><br/>
      <b>Kinetic tremor</b>
    </td>
    <td align="center">
      <img src="demos/yande_2_motion.gif" width="260"/><br/>
      <b>Pronation-supination</b>
    </td>
  </tr>
</table>
