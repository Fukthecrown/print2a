# SW1522
by nguyenkvvn

A fork of the SW1522 v1.0 baseline to support S&amp;W M&amp;P 15-22 kits

Public Release v1.0

## Description
The SW1522 is an AR-15 lower, derived off the DS1913 v1.0 baseline (which is based off the Disruptive Solutions AR-15 lower from FOSSCAD), specifically made to support Smith & Wesson M&P 15-22 kits. 

Features to it include a 1913 rail on the rear for mounting compact braces or stocks, bolt-catch delete for added reinforcement, and integrated bolt-press-forward to increase reliability. The lower is refined specifically for 3D printing, accounting for shrinkage and tolerances (meaning your printer must be 100% calibrated), along with modifications needed to make the lower functional, as the original was published as untested. 

This model has two variants:
* **SW1522** - Made for use with _only_ S&W 15-22 magazines. Requires the S&W 15-22 specific bolt-hold open.
* **CM1522** - Made for compatiblity with CMMG mags, Vinh's AR-15 22 LR mags, and S&W 15-22 magazines, but _without_ last-round-bolt-hold-open.

## Materials Required
1. **S&W M&P 15-22 Upper Reciever** - Proprietary S&W M&P 15-22 upper reciever. This lower reciever is *NOT* compatible with mil-spec AR-15 upper recievers.
2. **AR-15 Lower Parts Kit** - A lower parts kit of your choosing will do. Mil-spec is the minimum, however the lower's tolerances is revised for the S&W 15-22's lower parts kit. (Don't forget your choise of grip, and fire control group.)

## WARNING!
Do *NOT* under any circumstance use this design with ANY upper receiver that requires a buffer tube. Catastrophic, and FATAL, damage *WILL* occur. The designer, and any affiliated or non-affiliated groups, cannot be held responsible or liable for any injuries or damages that occur with your use of this model.

It is imperative you read this entire document before beginning this project.

## Printing Tips
* eSUN PLA+ is the _required_ filament.
* Print HOT and SLOW for maximum bonding and strength. (50 mm/s and 230 C is recommended.)
* It is strongly recommended that your x-axis, y-axis, and z-axis stepper motors are calibrated 100%.
* Ironing is recommended.

## FAQ

*Q:* Why does my fire control group pins or fire-select seem not to fit? They are a bit wider than the reciever.

*A:* OEM Smith & Wesson M&P 15-22 pins are much longer, as is the fire safety select. You can use it, but it will protrude one side or another ever so slightly. I left the lower mil-spec so that you can customize it with other mil-spec accessories.

## Changelog

* Public Release v1.0
> - STEP files included.
> - Renamed confusing SC1522 to CM1522.

* Private Beta v0.3
> - (SW1522) Revised magazine fitment
> - (All) Omitted non-functional front takedown retention
> - (Documentation) Inserted FAQ
> - (CM1522) Revised grip fitment
> - (CM1522) Flared grip screw

* Private Beta v0.2
> - (SW1522) Fixed missing bolt catch nub
> - (SW1522) Revised magazine fitment
> - (SW1522) Revised grip fitment
> - (SW1522) Flared grip screw

* Private Beta v0.1
> - Initial beta

## License
> MIT License

##### Vinh's Stipulations in addition to MIT License
* I require you do not charge others for access, nor rehost outside of personal, private archives. This introduces the possibility of stale files and out-of-date shares, which may be dangerous of a critical fix/patch distribution is required.
* Official sources shall only include Vinh's GitHub (@nguyenkvvn), and Deterrence Dispensed's LBRY archives. (Hot linking is perfectly okay!)