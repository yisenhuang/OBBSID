## OBBSID Dataset

**OBBSID** (OBB-based Surgical Instrument Detection) is a large-scale benchmark dataset for oriented bounding box (OBB) detection of surgical instruments in minimally invasive surgery (MIS).

### Dataset Statistics

| Item | Details |
| ---- | ------- |
| Total frames | 8,709 high-resolution frames |
| Real images | 5,007 (Prince of Wales Hospital) |
| Simulated images | 3,702 |
| Annotations | 10,756 expert-labeled instances |
| Instrument categories | 9 |
| Data split | Train 6,967 / Validation 870 / Test 872 |

### Instrument Categories

Ultrasonic knife · Blade electrodes · Graspers · Scissors · Needle holders · Knot pusher · Vessel sealing tool · Clamps · Suckers

### Why Oriented Bounding Boxes?

OBBSID is the first dataset specifically designed for OBB-based surgical instrument detection. Compared to conventional horizontal bounding boxes, OBBs provide tighter fits around elongated instruments, reduce background noise, and encode precise orientation cues — making them ideal for real-time visual servoing and autonomous endoscope control.

### Citation

If you find this dataset useful in your research, please cite our paper:

> Yisen Huang et al., "Real-time multi-constraint control of autonomous flexible endoscope robots via finite-time neural optimization," *Engineering Applications of Artificial Intelligence*, 2026.
> https://www.sciencedirect.com/science/article/pii/S095219762601969X

### Access

> ⚠️ **Note**: This dataset is currently private. To request access to the dataset and the corresponding code, please contact the author: **Yisen Huang (yisenhuang@link.cuhk.edu.hk)**.
