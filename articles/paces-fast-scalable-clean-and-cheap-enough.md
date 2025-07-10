# Fast, scalable, clean, and cheap enough
How off-grid solar microgrids can power the AI race.\
By Kyle Baranko (Paces), Duncan Campbell (Scale Microgrids), Zeke Hausfather (Stripe),
James McWalter (Paces), Nan Ransohoff (Stripe)\
December 2024

_Please note that these are my **personal learning notes**. Do not take them at face value, as I may have missed important details or misunderstood certain parts. Please refer to the original article for the full context._

[Full White Paper here](https://www.offgridai.us/)

___

# Summary

## Context

- Hyperscalers need enormous amounts of power ASAP to power AI datacenters. Estimates range from **~30-300 GW by ~2030**.
- Procuring huge amounts of energy fast is **a strategic imperative** for hyperscalers
- **Grid expansion today in the US is slow**. Many believe the AI needs in the US will most likely be met by building colocated natural gas power plants.

## Key findings
- Off-grid solar microgrids are categorically **faster than new grid interconnections** (5+year queues) as well as **off-grid colocated gas turbines** (3+ year lead times).
- Off-grid solar microgrids today are **near cost parity with natural gas** and **cheaper than other clean alternatives**.
- Off-grid solar microgrids are **enormously scalable**, with >1,200 GW of datacenter potential in the US southwest alone.
- Between **0.4 billion tons** (30 GW new datacenters) and **4.1 billion tons** (300 GW new datacenters) of **CO₂ emissions could be avoided** between now and 2030 if every new AI datacenter was built using the 90% solar configuration.

# What do hyperscalers care about?

- The goal is to **maximize absolute compute ASAP**, which means accessing huge amounts of energy ASAP.
- Datacenters for **inference** vs **training** have different energy requirements.
    - Inference requires proximity to end-users and a high degree of reliability and redundancy in energy supply.
    - Training datacenters are more geographically flexible and can tolerate less redundancy, though high GPU costs still penalize any significant downtime.
- Training datacenters likely represent about half of new capacity expected by 2030.

# What are the current options?

1. **Expand the grid**.
    - The problem is that this takes a long time and is expensive.
2. **Restart mothballed facilities like Three Mile Island**.
    - The problem is there’s a limited number of these opportunities.
3. **Build off-grid, colocated clean-firm energy like geothermal or new nuclear facilities**.
    - These are unlikely to get built at the speed and scale necessary to meet near-term AI energy needs.
4. **Build new datacenters and new energy infrastructure next to existing utility-scale solar and wind**.
    - However, the opportunity here is limited as few utilities have excess existing clean energy capacity that is not currently being utilized.
5. **Power datacenters with rented, portable gas/diesel generators until permanent power can be secured**.
    - This is a reasonable stop-gap solution to get power fast, though the scalability of this strategy is currently limited.
6. **Build off-grid, colocated natural gas**.
    - Many groups we spoke to consider this to be the most viable near-term option.

**Off-grid solar microgrids have been conspicuously absent** from most hyperscalers’ plans.\
They are likely **the only clean solution** that could also achieve the scale and speed requirements described.

# The case for off-grid solar microgrids

## Cost: How much would this cost?

- While costs increase steeply as the portion of renewable generation approaches 100%, **costs are quite competitive up to around 90%** of lifetime hourly energy demand met by solar+storage.
- For nearly the same LCOE (Levelized Cost of Energy) as an off-grid natural gas turbine, you can get a microgrid that’s **44% renewable**.
- For a significantly lower LCOE than the Three Mile Island nuclear reactor restart + minor delivery charges, you can get a microgrid that is **90% renewable**.
- Solar+storage+nat gas generators could be even **more favorable** via additional cost optimization.
- The uptime requirements for AI training datacenters may offer opportunities to **eliminate generators entirely**.

<img src="https://www.offgridai.us/images/image12.png" height="300" />

## Scale: Is there enough land to power the near-term AI race? Where?

- There’s **>1,200 GW worth of sites** suitable for AI datacenter capacity in the US Southwest.
- The vast majority of sites are **in West Texas**.
    - This is largely due to gas pipeline density. If you relax this constraint by moving 100% off grid, you can build almost anywhere.
- Most of this suitable land is **privately owned**.
    - Meaning most of this is commercially viable today.
- Most eligible parcels in Paces’ data set have the **contact information for the owner**.
    - These aren’t just hypothetical sites, but potentially buyable land.

<img src="https://www.offgridai.us/images/image14.png" height="300" />


## Speed: How fast could these be built?

-  ‘Typical’ time to deployment would be **~2-4 years**.
    - This could be done faster by a very motivated and competent builder.
- Off-grid solar is **meaningfully faster** than adding capacity to the grid via waiting for interconnection.
    - Queues for which are around 5 years in most parts of the country.
- Off-grid solar is also **faster than colocated natural gas turbines** (at least today).
    - Turbine lead times are long—currently 3+ years.
- The one thing that could be faster is **rented portable generation**.
    - This is typically a stop-gap solution due to high costs and worse reliability.
    - Additionally, the near-term scale potential is limited.

<img src="https://www.offgridai.us/images/image3.png" height="300" />


## Climate: What would the emissions impact be?

- The use of off-grid solar microgrids to meet all expected datacenter growth could result in **substantial emissions reductions**.
- Between **0.4 billion tons** (30 GW new datacenters) and **4.1 billion tons** (300 GW new datacenters) of **CO₂ emissions could be avoided** between 2026 and 2030.

<img src="https://www.offgridai.us/images/image8.png" height="300" />

# If this is so great, why isn’t it happening?

- **Cost**
- Massive datacenters dedicated to training only are a **recent phenomenon**, , and datacenter designers have historically been **skeptical of off-grid solutions** due to the perceived need to optimize for uptime reliability.
- **Inertia**: this hasn’t been done before.

# Conclusion

- Off-grid solar microgrids offer a fast path to power AI datacenters at enormous scale.
- The tech is mature.
- The suitable parcels of land in the US Southwest are known.
- This solution is faster than most alternatives.
- **The advantages to whoever moves on this quickly could be substantial**.