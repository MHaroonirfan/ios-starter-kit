If you provide an initial value for a constant or variable at the point that it’s defined, Swift can almost always infer the type to be used for that constant or variable, as described in Type Safety and Type Inference.

the print(_:separator:terminator:)


“The separator and terminator parameter have default values, so you can omit them when you call this function.”


# Type Aliases

Type aliases define an alternative name for an existing type. You define type aliases with the typealias keyword.

`typealias AudioSample = UInt16`

Once you define a type alias, you can use the alias anywhere you might use the original name

`var maxAmplitudeFound = AudioSample.min
// maxAmplitudeFound is now 0`

