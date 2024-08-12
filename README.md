Here’s a polished version of your README file:

---

# ts-x

**ts-x** is a Python library designed for time series modeling, enabling the simultaneous inclusion of trigonometric seasonalities and exogenous data as features. This project aims to provide a robust and flexible framework for developing advanced time series models that can handle complex seasonal patterns and incorporate external data to improve forecasting accuracy.

## Key Features

- **Trigonometric Seasonalities**: Effortlessly incorporate seasonal components using trigonometric functions, allowing for more accurate modeling of cyclical patterns in your time series data.
- **Exogenous Data Integration**: Seamlessly include external variables (exogenous data) as additional features, enhancing the predictive power of your models.
- **User-Friendly API**: Intuitive and easy-to-use API, making it accessible for both novice and experienced users.
- **Extensible Framework**: Flexible design that allows for the integration of custom components and models.

## Installation

You can install **ts-x** via pip:

```bash
pip install ts-x
```

## Getting Started

Here’s a simple example of how to use **ts-x** to create a time series model:

```python
import tsx

# Load your time series data
data = ...

# Define trigonometric seasonalities
seasonalities = tsx.Seasonalities(periods=[7, 365])

# Include exogenous data
exogenous = ...

# Create and fit the model
model = tsx.TimeSeriesModel(seasonalities=seasonalities, exogenous_data=exogenous)
model.fit(data)

# Make predictions
predictions = model.predict(future_steps=30)
```

For more detailed usage and examples, please refer to the [documentation](#).

## Contributing

Contributions are welcome! If you have ideas for new features, improvements, or bug fixes, please open an issue or submit a pull request. Make sure to check our [contribution guidelines](CONTRIBUTING.md) before you start.

## License

This project is licensed under the BSD-3-Clause License. See the [LICENSE](LICENSE) file for details.

---

This version provides a clearer structure, emphasizes key features, and enhances readability. If you have any additional details or sections you'd like to include, feel free to let me know!
