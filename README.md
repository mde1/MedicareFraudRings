# MedicareFraudRings
Databases used for a research project testing the effect of adding OSINT relationships to medicare claims on community detection of fraud rings. There are 4 databases

-- Base - Vanilla Medicare claims import (2019-2021 claims Parts B and D)
-- Base_KNN - Medicare claims import (2019-2021 claims Parts B and D) with FastRP embeddings and KNN-derived relationships
-- OSINT - Medicare claims import (2019-2021 claims Parts B and D) with confirmed business relationships added between 100 labeled nodes
-- OSINT_KNN - Medicare claims import (2019-2021 claims Parts B and D) with both OSINT-derived and KNN-derived edges added
