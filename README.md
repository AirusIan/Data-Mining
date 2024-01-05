# Data-Mining
# Using the Dataset below
1. Title: Glass Identification Database

2. Sources:
    (a) Creator: B. German
        -- Central Research Establishment
           Home Office Forensic Science Service
           Aldermaston, Reading, Berkshire RG7 4PN
    (b) Donor: Vina Spiehler, Ph.D., DABFT
               Diagnostic Products Corporation
               (213) 776-0180 (ext 3014)
    (c) Date: September, 1987

3. Past Usage:
    -- Rule Induction in Forensic Science
       -- Ian W. Evett and Ernest J. Spiehler
       -- Central Research Establishment
          Home Office Forensic Science Service
          Aldermaston, Reading, Berkshire RG7 4PN
       -- Unknown technical note number (sorry, not listed here)
       -- General Results: nearest neighbor held its own with respect to the
             rule-based system

4. Relevant Information:n
      Vina conducted a comparison test of her rule-based system, BEAGLE, the
      nearest-neighbor algorithm, and discriminant analysis.  BEAGLE is 
      a product available through VRS Consulting, Inc.; 4676 Admiralty Way,
      Suite 206; Marina Del Ray, CA 90292 (213) 827-7890 and FAX: -3189.
      In determining whether the glass was a type of "float" glass or not,
      the following results were obtained (# incorrect answers):

             Type of Sample                            Beagle   NN    DA
             Windows that were float processed (87)     10      12    21
             Windows that were not:            (76)     19      16    22

      The study of classification of types of glass was motivated by 
      criminological investigation.  At the scene of the crime, the glass left
      can be used as evidence...if it is correctly identified!

5. Number of Instances: 214

6. Number of Attributes: 10 (including an Id#) plus the class attribute
   -- all attributes are continuously valued

7. Attribute Information:
   1. Id number: 1 to 214
   2. RI: refractive index
   3. Na: Sodium (unit measurement: weight percent in corresponding oxide, as 
                  are attributes 4-10)
   4. Mg: Magnesium
   5. Al: Aluminum
   6. Si: Silicon
   7. K: Potassium
   8. Ca: Calcium
   9. Ba: Barium
  10. Fe: Iron
  11. Type of glass: (class attribute)
      -- 1 building_windows_float_processed
      -- 2 building_windows_non_float_processed
      -- 3 vehicle_windows_float_processed
      -- 4 vehicle_windows_non_float_processed (none in this database)
      -- 5 containers
      -- 6 tableware
      -- 7 headlamps

8. Missing Attribute Values: None

# HW3
1.Perform equal-width with ten bins, equal-frequency with ten bins, and the entropy-based discretization on the continuous attributes

2.For each discretization method, perform the selective naïve Bayes to find an attribute subset for classification

# HW4
Perform equal-width with ten bins, equal-frequency with ten bins, and the entropy-based discretization on the continuous attributes.  Then apply the naïve Bayesian classifier when the evaluation method is 5-fold cross validation
