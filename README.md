
package com.example.unitconverter

import org.junit.Assert.assertEquals
import org.junit.Test

class UnitConverterTest {

    @Test
    fun testTemperatureConversion() {
        val converter = MainActivity()
        assertEquals(32.0, converter.convertTemperature(0.0, "Celsius", "Fahrenheit"), 0.01)
        assertEquals(273.15, converter.convertTemperature(0.0, "Celsius", "Kelvin"), 0.01)
    }

    @Test
    fun testLengthConversion() {
        // Add length tests
    }

    @Test
    fun testWeightConversion() {
        // Add weight tests
    }
}
