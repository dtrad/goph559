Geostatistics allows for the combination of different physical properties into a single value by employing methods that model spatial relationships and correlations between these properties. Here's how this process works:

### 1. **Modeling Spatial Correlations:**
   - Geostatistics is based on the idea that the spatial distribution of a physical property can be described by statistical relationships between the values of that property at different locations. These relationships are often quantified using tools like variograms, which model how the similarity between two points decreases with increasing distance.

### 2. **Multivariate Geostatistics:**
   - In many cases, multiple physical properties (e.g., porosity, permeability, seismic velocity) are related and can be spatially correlated. Multivariate geostatistics extends the traditional univariate approach to handle multiple variables simultaneously. By analyzing the cross-correlations between these variables, geostatistics can create models that account for the joint spatial behavior of all involved properties.

### 3. **Co-Kriging:**
   - Co-kriging is a geostatistical technique that allows for the estimation of a primary variable (e.g., porosity) by incorporating secondary variables (e.g., seismic impedance, gamma-ray log) that are correlated with the primary variable. The method uses the spatial correlation structure of both the primary and secondary variables to make more accurate predictions at unsampled locations. The result is a combined value that reflects the influence of all the properties considered.

### 4. **Geostatistical Simulation:**
   - Simulation methods, such as sequential Gaussian simulation or sequential indicator simulation, allow for the generation of multiple realizations of a physical property, considering both its own spatial variability and its correlation with other properties. These simulations can combine different physical properties into one probabilistic model, providing a more comprehensive representation of the subsurface.

### 5. **Linear Models of Coregionalization (LMC):**
   - LMC is a technique used to model the spatial variability of multiple variables simultaneously. It assumes that the spatial variability of each variable can be described by a linear combination of common spatial structures. By fitting these structures to the observed data, LMC enables the combination of different physical properties into a unified model that captures their spatial relationships.

### 6. **Principal Component Analysis (PCA):**
   - PCA is sometimes used in geostatistics to reduce the dimensionality of multivariate data, combining different physical properties into fewer uncorrelated principal components. These components can then be used in subsequent geostatistical analysis, providing a way to combine and interpret the influence of multiple properties in a single value or model.

### 7. **Joint Inversion:**
   - In some cases, geostatistics is used in conjunction with joint inversion techniques, where different types of geophysical data (e.g., seismic, gravity, magnetics) are inverted simultaneously to produce a single model that integrates multiple physical properties. This approach leverages the spatial correlations and complementary information provided by different datasets to produce a combined value or model.

### 8. **Indicator Kriging:**
   - When dealing with categorical data (e.g., lithology types), indicator kriging can be used to combine different physical properties by transforming them into binary indicators. The method then estimates the probability of each category at unsampled locations, effectively combining different properties into a probability map.

By leveraging these methods, geostatistics provides a powerful framework for integrating and combining different physical properties into a coherent spatial model, leading to more accurate and reliable subsurface interpretations.