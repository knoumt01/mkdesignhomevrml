#VRML V2.0 utf8
#finalproject-knouff.wrl

# BACKGROUND
Background {
	groundColor 0 0.4 0
	skyColor 0 0 0.5
	}

# TURN OFF DEFAULT LIGHTING
NavigationInfo { 
	headlight FALSE
	type "EXAMINE"
}

# ADD DIRECTIONAL LIGHTING
DirectionalLight {
	ambientIntensity 0.5
	direction 0 -0.5 -0.25
	color 1 1 1
} # end directional light

# BUILDING FRONT
Transform {
	translation 0 -1.15 -7
	children [
		Shape {
			appearance Appearance {
				material Material {
					diffuseColor 0.5 0.5 0.5
				} # end material
				texture ImageTexture {
					url["frontofbuilding.jpg"]
				} # end texture
			} # end appearance
			geometry IndexedFaceSet {
				solid TRUE
				coord Coordinate {
					point [
						-2 0 2, # point 0
						2 0 2, # point 1
						2 2 2, # point 2
						-2 2 2, # point 3
					] # end point
				} # end coord
				coordIndex [
					0 1 2 3 0
				] # end coordIndex
				texCoord TextureCoordinate {
					point [
						0 0, # 0 lower left
						1 0, # 1 lower right
						1 1, # 2 upper right
						0 1, # 3 upper left
					] # end point
				} # end texcoord
				texCoordIndex[
					0 1 2 3 0 -1 # front
				] # texcoordindex
			} # end geometry
		} # end shape
	] # end children
} # end transform

# BUILDING
Transform {
	translation 0 -1.15 -7
	children [
		Shape {
			appearance Appearance {
				material Material {
					diffuseColor 0.5 0.5 0.5
				} # end material
				texture ImageTexture {
					url["siding.jpg"]
				} # end texture
			} # end appearance
			geometry IndexedFaceSet {
				solid TRUE
				coord Coordinate {
					point [
						-2 0 2, # point 0
						2 0 2, # point 1
						2 2 2, # point 2
						-2 2 2, # point 3
						2 2 -2, # point 4
						2 0 -2, # point 5
						-2 0 -2, # point 6
						-2 2 -2, # point 7
						-2 3 0, # point 8
						2 3 0 # point 9
					] # end point
				} # end coord
				coordIndex [
					1, 5, 4, 2, 1, -1 # right side
					6, 0, 3, 7, 6, -1, # left side
					5, 6, 7, 4, 5, -1, # back
					3, 2, 9, 8, 3, -1, # front roof
					4, 7, 8, 9, 4, -1, # rear roof
					7, 3, 8, 7, -1, # left side roof
					2, 4, 9, 2, -1, # right side roof
				] # end coordIndex
			} # end geometry
		} # end shape
	] # end children
} # end transform

# DRIVE WAY
Transform {
	translation 0 -1.15 -4
	children [
		Shape {
			appearance Appearance {
				material Material {
					diffuseColor 0.35 0.35 0.35
				} # end material
				texture ImageTexture {
					url["street.jpg"]
				} # end texture
			} # end appearance
			geometry Box {
				size 4 0.05 3
			} # end geometry
		} # end shape
	] # end children
} # end transform

# PATIO OF BUILDING
Transform {
	translation 0 -1.15 -3
	children [
		Shape {
			appearance Appearance {
				material Material {
					diffuseColor 1 1 1
				} # end material
				texture ImageTexture {
					url["patio.jpg"]
				} # end texture
			} # end appearance
			geometry IndexedFaceSet {
				solid TRUE
				coord Coordinate {
					point [
						-4 0 -2, # point 0
						-2 0 -2, # point 1
						-2 0.8 -2, # point 2
						-4 0.8 -2, # point 3
						-4 0 -4, # point 4
						-4 0.8 -4, # point 5
						-2 0 -4, # point 6
						-2 0.8 -4, # point 7
						-2.7 0 -2, # point 8
						-2.7 0.8 -2, # point 9
					] # end point
				} # end coord
				coordIndex [
					0, 8, 9, 3, 0, -1, # front (outside)
					8, 0, 3, 9, 8, -1, # front (inside)
					4, 0, 3, 5, 4, -1, # side (outside)
					0, 4, 5, 3, 0, -1, # side (inside)
					4, 6, 7, 5, 4, -1, # rear (inside)
					6, 4, 5, 7, 6, -1, # rear (outside)
					4, 0, 1, 6, 4, -1, # ground
				] # end coordIndex
				texCoord TextureCoordinate {
					point [
						0 1, #0 upper left
						.5 1, #1 upper middle
						1 1, #2 upper right
						0 .5, #3 mid left
						.5 .5, #4 center
						1 .5, #5 mid right
						0 0, #6 lower left
						.5 0, #7 lower middle
						1 0, #8 lower right
					] # end point
				} # end texturecoordinate
				texCoordIndex[
					1, 4, 5, 2, 1, -1, # front
					1, 4, 5, 2, 1, -1, # front
					1, 4, 5, 2, 1, -1, # side
					1, 4, 5, 2, 1, -1, # side
					1, 4, 5, 2, 1, -1, # rear
					1, 4, 5, 2, 1, -1, # rear
					0, 3, 4, 1, 0, -1 # patio
				] # end text coord index
			} # geometry
		} # end shape
	] # end children
} # end transform

# ROUNDABOUT
Transform {
	translation 0 -1.15 1.8
	children [
		Shape {
			appearance Appearance {
				material Material {
					diffuseColor 0.4 0.4 0.4
				} # end material
				texture ImageTexture {
					url["street.jpg"]
				} # end texture
			} # end appearance
			geometry Cylinder {
				radius 5
				height 0.01
			} # end geometry
		} # end shape
	] # end children
} # end transform

# STREET
Transform {
	translation 0 -1.15 5
	children [
		Shape {
			appearance Appearance {
				material Material {
					diffuseColor 0.5 0.5 0.5
				} # end material
				texture ImageTexture {
					url["street.jpg"]
				} # end texture
			} # end appearance
			geometry Box {
				size 30 0.06 4.3
			} # end geometry
		} # end shape
	] # end children
} # end transform

# ROUNDABOUT CENTER
Transform {
	translation 0 -1.15 2
	children [
		Shape {
			appearance Appearance {
				material Material {
					diffuseColor 0 1 0
				} # end material
				texture ImageTexture {
					url["grass.jpg"]
				} # end texture
			} # end appearance
			geometry Cylinder {
				radius 2.65
				height 0.02
			} # end geometry
		} # end shape
	] # end children
} # end transform

# TREE PROTOTYPE
PROTO Tree [
	exposedField SFVec3f translation 0 0 0
]
{
	Transform {
		translation IS translation
		children [
			Shape {
				appearance Appearance {
					texture ImageTexture {
						url [ "tree1.gif" ]
					} # end texture
				} # end appearance
				geometry Box {
					size 2.5 2.5 .01
				} # end geometry
			} # end shape
			Shape {
				appearance Appearance {
					texture ImageTexture {
						url [ "tree1.gif" ]
					} # end texture
				} # end appearance
				geometry Box {
					size 0.01 2.5 2.5
				} # end geometry
			} # end shape
		] # end children
	} # end transform
} # end proto definition

# MAILBOX PROTOTYPE
PROTO Mailbox [
	exposedField SFVec3f translation 0 0 0
	exposedField SFRotation rotation 0 0 0 0
]
{
	Transform {
		translation IS translation
		rotation IS rotation
		children [
			Shape {
				appearance Appearance {
					material Material {
						diffuseColor 0.2 0.2 0.2 
					} # end material
				} # end appearance
				geometry Box {
					size 0.6 0.3 0.3
				} # end geometry
			} # end shape
		] # end children
	} # end transform
} # end proto definition

# MAILBOX STAND PROTOTYPE
PROTO MailboxStand [
	exposedField SFVec3f translation 0 0 0
	exposedField SFRotation rotation 0 0 0 0
]
{
	Transform {
		translation IS translation
		rotation IS rotation
		children [
			Shape {
				appearance Appearance {
					material Material {
						diffuseColor 1 1 1
					} # end material
					texture ImageTexture {
						url["benchtex.jpg"]
					} # end texture
				} # end appearance
				geometry Box {
					size 0.2 0.7 0.2
				} # end geometry
			} # end shape
		] # end children
	} # end transform
} # end proto definition

# DISPLAY TREES
Tree {
	translation 1.4 0 1.6
}
Tree {
	translation -1.4 0 1.6
}

# DISPLAY MAILBOXES
Mailbox {
	translation 4.65 -0.6 -0.5
	rotation 0 1 0 0.5
}
MailboxStand {
	translation 4.65 -0.9 -0.5
	rotation 0 1 0 0.5
}
Mailbox {
	translation 4.3 -0.6 -1.15
	rotation 0 1 0 0.5
}
MailboxStand {
	translation 4.3 -0.9 -1.15
	rotation 0 1 0 0.5
}
Mailbox {
	translation 4.45 -0.6 -0.81
	rotation 0 1 0 0.5
}
MailboxStand {
	translation 4.45 -0.9 -0.81
	rotation 0 1 0 0.5
}
Mailbox {
	translation 4.83 -0.6 -0.16
	rotation 0 1 0 0.5
}
MailboxStand {
	translation 4.83 -0.9 -0.16
	rotation 0 1 0 0.5
}

# TOP OF BENCH
Transform {
	translation 0 -0.7 2
	children [
		Shape {
			appearance Appearance {
				material Material {
					diffuseColor 1 1 1
				} # end material
				texture ImageTexture {
					url["benchtex.jpg"]
				} # end texture
			} # end appearance
			geometry Box {
				size 0.8 0.125 0.4
			} # end geometry
		} # end shape
		Sound {
			source AudioClip {
				loop TRUE
				url ["birds.wav"]
			} # end audio clip
		} # end sound
		DEF ts TouchSensor {}
	] # end children
} # end transform

PROTO BenchLeg [
	exposedField SFVec3f translation 0 0 0
]
{
	Transform {
		translation IS translation
		children [
			Shape {
				appearance Appearance {
					material Material {
						diffuseColor 1 1 1
					} # end material
					texture ImageTexture {
						url["benchtex.jpg"]
					} # end texture
				} # end appearance
				geometry Cylinder {
					radius 0.1
					height 0.45
				} # end geometry
			} # end shape
		] # end children
	} # end transform
} # end proto definition

BenchLeg {
	translation 0.25 -1 2
}

BenchLeg {
	translation -0.25 -1 2
}

# TEXT
Transform {
	translation -3.3 -0.7 -4.9
	children [
		Shape {
			appearance Appearance {
				material DEF theColor Material {
					diffuseColor 1 0 0
				} # end material
			} # end appearance
			geometry Text {
				string "3236"
				fontStyle FontStyle {
					size .1
				} # end fontstyle
			} # end text
		} # end shape
	] # end children
} # end transform

# INTERPOLATOR FOR CHANGING COLOR OF SIGN
DEF TIMER TimeSensor {
	cycleInterval 5
	loop TRUE
}
DEF COLORCHANGER ColorInterpolator {
	key [
		0
		.33
		.66
		1
	] # end key
	keyValue [
		1 0 0
		0 1 0
		0 0 1
		1 0 0
	] # end keyvalue
} # end colorchanger
ROUTE TIMER.fraction_changed TO COLORCHANGER.set_fraction
ROUTE COLORCHANGER.value_changed TO theColor.set_diffuseColor

# BALLS ON PATIO
PROTO Ball [
	exposedField SFVec3f translation 0 0 0
	exposedField SFVec3f scale 1 1 1
]
{
	Transform {
		translation IS translation
		scale IS scale
		children [
			Shape {
				appearance Appearance {
					material Material {
						diffuseColor 0 0 1
					} # end material
				} # end appearance
				geometry Sphere {
					radius 0.1
				} # end geometry
			} # end shape
		] # end children
	} # end transform
} # end proto definition

Ball {
	translation -3.3 -1.1 -6
	scale 1 1 1
}

Ball {
	translation -3.6 -1.15 -6.2
	scale 0.7 0.7 0.7
}

# MAILBOX FLAG
Transform {
	translation 5 -0.6 0
	scale 0.1 0.1 0.1
	children [
		Shape {
			appearance Appearance {
				material Material {
					diffuseColor 1 0 0
				} # end material
			} # end appearance
			geometry Extrusion {
				crossSection [
					0 1,
					-1 -1,
					1 -1,
					0 1,
				] # end cross section
				spine [
					0 0 0,
					0 .2 0,
				] # end spine
			} # end extrusion
		} # end shape
	] # end children
} # end transform

# SENSOR (OTHER THAN TIME SENSOR)
# ADD DIRECTIONAL LIGHTING

DEF CHANGECOLOR DirectionalLight {
	ambientIntensity 0
	direction 0 -0.5 -0.25
	color 1 0 0
} # end directional light

ROUTE ts.isActive TO CHANGECOLOR.on