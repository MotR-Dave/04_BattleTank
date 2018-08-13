Begin Map
   Begin Level
      Begin Actor Class=/Script/Engine.StaticMeshActor Name=SM_DoorFrame2 Archetype=/Script/Engine.StaticMeshActor'/Script/Engine.Default__StaticMeshActor'
         Begin Object Class=/Script/Engine.StaticMeshComponent Name="StaticMeshComponent0" Archetype=StaticMeshComponent'/Script/Engine.Default__StaticMeshActor:StaticMeshComponent0'
         End Object
         Begin Object Name="StaticMeshComponent0"
            StaticMesh=StaticMesh'/Game/StarterContent/Props/SM_DoorFrame.SM_DoorFrame'
            StaticMeshDerivedDataKey="STATICMESH_BA08C66E86EF48C993A163FC0A9ADF67_228332BAE0224DD294E232B87D83948F1$2e0_231CF0BF4426F908E9D6248709E1BABD0000000001000000010000000100000001000000010000000000000000000000000000004000000000000000010000000000803F0000803F0000803F0000803F00000000050000004E6F6E65000000803F00000000000000410000000000003442030303000000000"
            VisibilityId=18
            RelativeLocation=(X=489.042267,Y=-95.905670,Z=20.034523)
            CustomProperties 
         End Object
         StaticMeshComponent=StaticMeshComponent0
         RootComponent=StaticMeshComponent0
         ActorLabel="SM_DoorFrame2"
      End Actor
      Begin Actor Class=/Game/Openable_Door_BP.Openable_Door_BP_C Name=Openable_Door_BP Archetype=/Game/Openable_Door_BP.Openable_Door_BP_C'/Game/Openable_Door_BP.Default__Openable_Door_BP_C'
         Begin Object Class=/Script/Engine.TimelineComponent Name="Timeline_0"
         End Object
         Begin Object Class=/Script/BuildingEscape.OpenDoor Name="OpenDoor" Archetype=OpenDoor'/Game/Openable_Door_BP.Openable_Door_BP_C:OpenDoor_GEN_VARIABLE'
         End Object
         Begin Object Class=/Script/Engine.StaticMeshComponent Name="StaticMeshComponent0" Archetype=StaticMeshComponent'/Game/Openable_Door_BP.Default__Openable_Door_BP_C:StaticMeshComponent0'
         End Object
         Begin Object Name="Timeline_0"
            TheTimeline=(Length=2.000000,InterpFloats=((FloatCurve=CurveFloat'/Game/Openable_Door_BP.Openable_Door_BP_C:CurveFloat_0',TrackName="NewTrack_0",FloatPropertyName="Timeline_0_NewTrack_0_CF097677455833CE12F6D5A0F5CFB1E4")),TimelinePostUpdateFunc=Openable_Door_BP.Timeline_0__UpdateFunc,TimelineFinishedFunc=Openable_Door_BP.Timeline_0__FinishedFunc,PropertySetObject=Openable_Door_BP_C'Openable_Door_BP',DirectionPropertyName="Timeline_0__Direction_CF097677455833CE12F6D5A0F5CFB1E4")
            bNetAddressable=True
            CreationMethod=UserConstructionScript
         End Object
         Begin Object Name="OpenDoor"
            PressurePlate=TriggerVolume'TriggerVolume_1'
            bNetAddressable=True
            CreationMethod=SimpleConstructionScript
         End Object
         Begin Object Name="StaticMeshComponent0"
            RelativeLocation=(X=485.000000,Y=-140.000000,Z=20.000000)
            RelativeRotation=(Pitch=0.000000,Yaw=-179.999969,Roll=0.000000)
         End Object
         OpenDoor=OpenDoor
         Timeline_0=TimelineComponent'Timeline_0'
         StaticMeshComponent=StaticMeshComponent0
         RootComponent=StaticMeshComponent0
         ActorLabel="Openable_Door_BP"
      End Actor
   End Level
Begin Surface
End Surface
End Map
