---
name: "Add Operator"
about: Add a new ONNX operator

---

👋 Hey, thank for contributing! Please fill out the template below 😀


# New Operator

<!-- A clear and concise description of what the operator does. Link to related issues and PRs. -->

## Author Checklist

- [ ] I have read the [`AddNewOp`](https://github.com/onnx/onnx/blob/master/docs/AddNewOp.md) documentation

### Operator Proposal Checklist

- [ ] This operator cannot be a [function]() because <!-- why? --> (~delete~ if you are proposing a function)
- [ ] This operator is used in this public model: <!-- link to public code -->
- [ ] This operator is implemented in these frameworks:
  - <!-- Link to numpy documentation if present in numpy: https://docs.scipy.org/doc/numpy/reference/generated/numpy.clip.html -->
  - <!-- Link to documentation in ML frameworks: https://pytorch.org/docs/stable/torch.html#torch.clamp -->

### Operator Definition Checklist
- [ ] The description is unambiguous, using mathematical formulae or psuedocode
- [ ] The description contains an example
- [ ] The description references the source of the operator in the corresponding framwork
- [ ] I have written a complete reference implementation in Python
- [ ] I have correctly [versioned](https://github.com/fdwr/onnx/blob/master/docs/Versioning.md#operator-versioning) the operator
- [ ] I have written unit tests to cover main usage and corner cases
- [ ] I have run the [script](https://github.com/onnx/onnx/blob/master/tools/update_doc.sh) to update the docs and generate the test data
- [ ] I have written a [shape inference function](https://github.com/onnx/onnx/blob/master/onnx/test/shape_inference_test.py)
